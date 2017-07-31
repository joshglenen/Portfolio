## Welcome

Thank you for visiting my portfolio. This is not intended to be a comprehenisive resume. Here I will upload open source projects I have completed as well as describe my past accomplishements. If you would like to know more about me or view my resume, visit [linkedin.](https://www.linkedin.com/in/joshglenen/)

### My C# Projects

<!---------------------------------------------------------------------->
Talking Clock: [Link](https://github.com/joshglenen/2017-Projects/blob/master/Talk_Clk_Portable.zip)

<details> 
  <summary>View Main Class</summary>
  
```markdown
        
        //Global Timer
        Timer timer = new Timer();
        //Global Icon 
        private NotifyIcon myTray = new NotifyIcon();

        public MainWindow()
        {
            InitializeComponent();
            Hide();
            if (Process.GetProcessesByName(Process.GetCurrentProcess().ProcessName).Length > 1)
            {
                Close();
                return;
            } //Allows only one persistance of the program to run
            CreateIcon();
            MyWinFormsTimer(true);

        }

        public void CreateIcon()
        {
            ContextMenu myMenu = new ContextMenu();
            MenuItem myItem1 = new MenuItem();
            MenuItem myItem2 = new MenuItem();
            MenuItem myItem3 = new MenuItem();

            //creates the icon and message
            myTray.Icon = new Icon(@"Clock.ico");
            myTray.Visible = true;
            myTray.Text = "Working";
            myTray.ShowBalloonTip(1500, "Talking Clock", "Your talking clock is now active and working!", ToolTipIcon.None);
            
            //creates a list of menu items in context menu
            myMenu.MenuItems.AddRange(new MenuItem[] {myItem1, myItem2});
            myItem1.Index = 0;
            myItem1.Text = "Exit";
            myItem1.Click += new EventHandler(ExitClicked);
            myItem2.Index = 1;
            myItem2.Text = "About";
            myItem2.Click += new EventHandler(AboutClicked);
            myTray.ContextMenu = myMenu;

         
        } //Creates a simple icon in the system tray
        private void AboutClicked(object sender, EventArgs e)
        {
            myTray.ShowBalloonTip(1000, "About Talking Clock", "Talking clock is a program that will act as an hourly time notifier to help me keep on track of my daily routine", ToolTipIcon.Info);

        } //Info on program
        private void ExitClicked(object sender, EventArgs e)
        {
            myTray.Visible = false;
            Close();
        } //Exit Option

        public void MyWinFormsTimer(bool On = false) 
        {
            if (!On) // default
            {
                timer.Enabled = false;
            }
            else
            {
                timer.Enabled = true;
                timer.Interval = MilliSecondsLeftTilTheHour();
                timer.Tick += new EventHandler(Timer_Tick);
            }

        } // Sets up or disables a timer to occur at regular interval
        private int MilliSecondsLeftTilTheHour()
        {
            int interval;
            int minutesRemaining = 59 - DateTime.Now.Minute;
            int secondsRemaining = 59 - DateTime.Now.Second;
            interval = ((minutesRemaining * 60) + secondsRemaining) * 1000;
            if (interval == 0) //quick calculation when caught up
            {
                interval = 60 * 60 * 1000;
            }
            return interval;
        } //returns an integer in miliseconds left until the next hour
        private void Timer_Tick(object sender, EventArgs e) 
        {
            int preSpeech = DateTime.Now.Hour + 1; //Program gets hour just before it changes due to millisecond inconsistancies, readjust makes up for that
            String postSpeech;
            postSpeech = "The time is ";
            if (preSpeech == 12)
            {
                postSpeech += "Noon.";
            }
            else if (preSpeech == 0)
            {
                postSpeech += "Midnight.";
            }
            else if ((preSpeech - 12) > 1)
            {
                preSpeech -= 12;
                postSpeech += preSpeech.ToString();
                postSpeech += " pm";
            }
            else
            {
                postSpeech += preSpeech.ToString();
                postSpeech += " am";
            }
            SpeakNow(postSpeech);
            timer.Interval = MilliSecondsLeftTilTheHour();
        } //Speaks time every hour depending on timer expiration
        private static void SpeakNow(string String)
        {
            SpeechSynthesizer synthesizer = new SpeechSynthesizer();
            synthesizer.Volume = 100;  // 0...100
            synthesizer.SelectVoiceByHints(VoiceGender.Female); 
            synthesizer.Rate = 1;     // -10...10
            synthesizer.SpeakAsync(String);
        } //Synthesizes string into audio
        
```
</details>
<!---------------------------------------------------------------------->


Notify Me: [No Link](https://example.com)

<details> 
  <summary>View Main Class</summary>
  
```markdown

Code Not Availible

```
</details>


### My Capstone Project

My capstone project was



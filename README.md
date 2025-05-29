<p>This project is a Google Apps Script that notifies a Discord server each time a new form is submitted.</p>

<h3>CONFIGURATION:</h3>

<p>0. Create your form using G-Form.</p>

<p>1. Click the three small dots to the right of the "Send" button.</p>

<p>2. Click on "Script Editor" and paste my script there.</p>

<p>3. Modify the "discordUrl" and "responseUrl" variables (the comments explain their purpose).</p>

<p>Next, you need to set up your triggers:</p>

<h4 style="color:red;">4.1 On the left, select the "Triggers" tab.</h4>

<p>4.2 Add a new trigger.</p>

<p>4.3 Configure the trigger as follows:</p>

<p>4.4 Choose the function to execute: "OnFormSubmit".</p>

<p>4.5 Choose the deployment to execute: "Head".</p>

<p>4.6 Select the event source: "From form".</p>

<p>4.7 Select an event type: "On form submit".</p>

<p>4.8 Failure notification setting: "Receive notification immediately".</p>

<p>4.9 Save the trigger with these settings.</p>

<p>4.10 You must grant permissions for the trigger to execute the code.</p>

<h3>CUSTOMIZATION:</h3>

<p>You can customize the message sent to your Discord server by modifying the createMessage() function. This function generates the message to be sent, and you can change the title, description, and fields of the message there. If you are not familiar with code, don't worry: every line where customization is possible has a comment added!</p>

<h3>Long live open source!</h3>

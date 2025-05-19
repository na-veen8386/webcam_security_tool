<div>
  <h1>Webcam_Security</h1>
  <p>This project is designed to secure organizations in the real world from cyber frauds performed by hackers.</p>
</div>

<div>
  <h2>🛡️ Web Cam Security from Spyware</h2>
  <p>
    A desktop application built with Python and Tkinter that implements a Physical Security Policy on webcam devices to prevent unauthorized spyware activities. 
    This project was developed as part of a Cybersecurity Internship at Supraja Technologies.
  </p>
</div>

<div>
  <h2>📌 Features</h2>
  <ul>
    <li>🔒 Prevents webcam access by spyware and unauthorized tools.</li>
    <li>✉️ Sends a secure OTP via email to verify user access.</li>
    <li>🧠 Implements basic UI with Tkinter for user interaction.</li>
    <li>📸 Protects webcam usage on personal and organizational computers.</li>
    <li>🖼️ Custom icon set using Base64 image encoding.</li>
    <li>📄 Displays project and developer information in a browser.</li>
  </ul>
</div>

<div>
  <h2>🧰 Tech Stack</h2>
  <ul>
    <li>Python 3.x</li>
    <li>Tkinter – GUI framework</li>
    <li>Pillow (PIL) – For image processing</li>
    <li>Base64 – For encoding image icons</li>
    <li>SMTP – Email service for OTP delivery</li>
    <li>HTML/CSS – For displaying project info via browser</li>
  </ul>
</div>

<div>
  <h2>📧 OTP Verification</h2>
  <ul>
    <li>The user is prompted to enter their email.</li>
    <li>An OTP is generated and sent using Gmail SMTP.</li>
    <li>Future security actions can be gated using OTP validation.</li>
  </ul>
</div>

<div> 
  <h2>⚙️ Installation & Execution</h2>
  <p>Follow the steps below to clone and run the Webcam Security Tool:</p>
  <pre><code>git clone https://github.com/na-veen8386/Webcam_Security.git
cd webcamsecurity_tool
pip install pillow secure-smtplib
python webcamsecurity_tool.py</code></pre>
</div>

<div>
  <h2>📧 Gmail App Password Creation Process</h2>
  <p>To allow your Python application to send emails via Gmail, follow these steps to generate an App Password:</p>

  <ol>
    <li>
      <strong>Enable 2-Step Verification</strong>
      <ul>
        <li>Go to <a href="https://myaccount.google.com/security" target="_blank">Google Account Security</a>.</li>
        <li>Under "Signing in to Google", enable <strong>2-Step Verification</strong>.</li>
      </ul>
    </li>
  </ol>
    <li>
      <strong>Generate an App Password</strong>
      <ul>
        <li>After enabling 2-Step Verification, go to the <a href="https://myaccount.google.com/apppasswords" target="_blank">App Passwords</a> page.</li>
        <li>You might need to re-enter your Google password.</li>
        <li>In the "Select app" dropdown, choose <strong>Mail</strong>.</li>
        <li>In the "Select device" dropdown, choose <strong>Other</strong>, then enter a custom name (e.g., <em>Python App</em>).</li>
        <li>Click <strong>Generate</strong>.</li>
        <li>A 16-character App Password will be displayed. Copy and use this password in your Python script instead of your regular Gmail password.</li>
      </ul>
    </li>
<ol>
    <li>
      <strong>Use in Python Code</strong>
      <p>Example SMTP configuration in Python:</p>
      <pre><code>import smtplib 
from email.message import EmailMessage

email_sender = 'your_email@gmail.com'
email_password = 'your_app_password'  # 16-character app password

msg = EmailMessage()
msg['Subject'] = 'Test Email'
msg['From'] = email_sender
msg['To'] = 'recipient@example.com'
msg.set_content('This is a test email sent from Python.')

with smtplib.SMTP_SSL('smtp.gmail.com', 465) as smtp:
    smtp.login(email_sender, email_password)
    smtp.send_message(msg)</code></pre>
    </li>
  </ol>

  <p><strong>Note:</strong> App passwords are only visible when generated. Keep it secure and do not share it publicly.</p>
</div>



<div>
  <h2>📃 Project Information</h2>
  <p>
    To view project & developer details:
  </p>
  <ul>
    <li>Click the “Project Info” button in the GUI (if implemented).</li>
    <li>A browser window opens with styled HTML containing internship info, developer names, dates, etc.</li>
  </ul>
</div>

<div>
  <h2>👨‍💻 Developers</h2>
  <table border="1" cellpadding="5" cellspacing="0">
    <thead>
      <tr>
        <th>Name</th>
        <th>Employee ID</th>
        <th>Email</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>K. Hemanth Kumar Reddy</td>
        <td>ST#IS#6406</td>
        <td>hemanthgreat100@gmail.com</td>
      </tr>
      <tr>
        <td>Kalanjeri Naveen Prasad</td>
        <td>ST#IS#6407</td>
        <td>kalamjerinaveenprasad@gmail.com</td>
      </tr>
      <tr>
        <td>Vadla Abdul Rahiman</td>
        <td>ST#IS#6408</td>
        <td>abdulrahimanvadla@gmail.com</td>
      </tr>
      <tr>
        <td>Dharshini Kuragayala</td>
        <td>ST#IS#6409</td>
        <td>dharshiniroyal5@gmail.com</td>
      </tr>
    </tbody>
  </table>
</div>

<div>
  <h2>📅 Project Timeline</h2>
  <table border="1" cellpadding="5" cellspacing="0">
    <tbody>
      <tr>
        <td><strong>Detail</strong></td>
        <td><strong>Date</strong></td>
      </tr>
      <tr>
        <td>Start Date</td>
        <td>26-05-2024</td>
      </tr>
      <tr>
        <td>End Date</td>
        <td>29-06-2024</td>
      </tr>
      <tr>
        <td>Status</td>
        <td>✅ Completed</td>
      </tr>
    </tbody>
  </table>
</div>

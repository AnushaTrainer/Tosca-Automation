🚀 Generate One-Time Passwords (TOTP) in Tosca – Simplify MFA/2FA Testing!

Tired of manually entering OTPs during your automation runs?
Here’s a ready-to-use Tosca solution that generates and stores valid 6-digit Time-based One-Time Passwords (TOTP) — compatible with Microsoft & Google Authenticator! 🔐

✅ Key Features
Generates valid 6-digit TOTP
Supports SHA1, SHA256, SHA512
Default Base32 encoding
Auto-stores OTP in Tosca buffer for downstream use
Built with .NET 8 using Otp.NET NuGet package

🧩 Output:
A buffer named OTP is automatically created and filled with the generated code.

⚙️ Quick Setup Steps:
1️⃣ Copy GenerateTOTP.dll and Otp.NET.dll to your Tosca TBox folder
2️⃣ Import Totp generation_Trial.tsu module into Tosca
3️⃣ Use the “Generate OTP” module in your test case and input your Base32 secret key
4️⃣ Access your OTP via buffer — B{OTP}

💡 Ideal for automating MFA/2FA login flows in Tosca without manual effort!

If you need customization or want to integrate this into enterprise test frameworks, connect with me 👇
https://www.linkedin.com/in/anusha-jyothi-612543286/ 

#Tosca #AutomationTesting #TOTP #MFA #2FA #TestAutomation #Tricentis #DotNet #AutomationTools

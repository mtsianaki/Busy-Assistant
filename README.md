## Installation | نصب

Busy Assistant is designed for Issabel PBX / Asterisk.  
Busy Assistant برای Issabel V5 طراحی شده است.

### Install from GitHub | نصب از GitHub

Login to your Issabel server as `root` and run the following commands:  
با کاربر `root` وارد سرور Issabel شوید و دستورات زیر را اجرا کنید:

```bash
cd /root
dnf install -y git
git clone https://github.com/mtsianaki/Busy-Assistant.git
cd Busy-Assistant
chmod +x install.sh
./install.sh

-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

The installer will automatically install the required files and configure Busy Assistant.
نصاب به‌صورت خودکار فایل‌های موردنیاز را نصب کرده و Busy Assistant را پیکربندی می‌کند.

During installation, required settings such as the Bale Bot Token will be requested.
در هنگام نصب، تنظیمات موردنیاز مانند توکن ربات Bale از شما درخواست می‌شود.

After installation, additional settings can be managed from the Busy Assistant web panel inside Issabel.
پس از نصب، تنظیمات تکمیلی از طریق پنل وب Busy Assistant داخل Issabel قابل مدیریت است.

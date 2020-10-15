# Dell 7460 Hackintosh with Opencore - Developer Machine Setup

- Opencore 0.6.1
- Installed on my 2nd drive. Had replaced that stock 1TB sata drive with a 128GB ssd. The first stock drive (128GB M.2) has the oem windows 10 home. Dual boot works well.

### Tools and Softwares working flawlessly
- Xcode 12 (I'm doing RN projects)
- Docker (alpine/nginx/php-fpm/mysql for api backend projects)
- Gimp
- VS Code
- Homebrew
- DuetDisplay (wired to an iPad)
- iMessage (linked to my iPhone as well)
- Slack


### Not working
- As expected, built-in wifi not working. Had to use a usb wifi card from TPLink (`TL-WN725N`). No AirDrop though.

- Built-in ethernet port also not working. Still un-able to figure out the fix for this. So i had to make full installer instead of recovery installer as i cannot download macOS over the internet during the installation. Lot of guides how to create a full installer, just google it. :)

- Initially, i have set ALC layout id to `11`. And there is no audio coming out thru the headphone jack. Bluetooth audio do works. But finally settled to setting it to `21` and then that issue was fixed.

- DRM contents on safari. Didn't bother to figure out fixing this, this is my dev laptop anyway. :P

- Having issue bluetooth pairing my Anne Pro2 kb. Works fine wired.

### TODO (Non-essential)
- Buy a compatible wifi card.
- Fix that ethernet port issue (detected but stays in-active). Port works well in Win10.
- Fix DRM issue.
- Lookout for update when we could utilize the GPU that comes wit this laptop.




**Have fun! Happy hackintoshing!**
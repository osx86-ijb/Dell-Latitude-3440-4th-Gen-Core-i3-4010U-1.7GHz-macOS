<h1 align="center">Dell Latitude 3440 4th Gen Core i3 4010U 1.7GHz OpenCore EFI files needed to boot macOS</h1>
<p align="center">OpenCore EFI for Dell Latitude 3440 4th Gen Core i3-4010U 1.7GHz</p> 
<p align="center">(Tested on Mojave/Catalina/Big Sur/Monterey/Ventura/Sonoma)</p>

<div align="center">

![Dell Latitude 3440 4th Gen Core i3 4010U](https://github.com/osx86-ijb/Dell-Latitude-3440-4th-Gen-Core-i3-4010U-1.7GHz-macOS/assets/67184728/78837259-f085-48ea-aa0b-46aaa9cd5ab8)

</div>

## DISCLAIMER

THIS INFORMATION/RESEARCH HAS BEEN DONE AND SHARED PURELY FOR EXPERIMENTAL AND RESEARCH PURPOSES, AND IS IN NO MAY MEANT TO PROMOTE CIRCUMVENTING OF ANYTHING THAT IS SOMEONE ELSE'S CORPORATE PRIVATE PROPERTY. THE INFORMATION LISTED HERE IS PURELY FOR EDUCATIONAL PURPOSES AND SHOULD YOU CHOOSE TO UTILIZE IT IN ANY WAY, I AM IN NO WAY RESPONSIBLE FOR ANY INJUNCTIONS/PROBLEMS THAT MAY OR MAY NOT ARISE AND/OR BE BROUGHT AGAINST ANOTHER PERSON FOR THEIR/YOUR CHOOSING TO HAVE DONE SO.


## NOTE :
  
#### KEEP IN MIND AND TAKE NOTE THAT THIS REPOSITORY HAS MULTIPLE BRANCHES USED TO SUPPORT EACH OF THE FOLLOWING VERSIONS OF MACOS AND SHALL BE BOTH SORTED / UPDATED ACCORDINGLY PER VERSION:
  
## macOS Mojave 10.14.6 (18G9323)
![Screen Shot 2023-09-02 at 7 18 24 AM](https://github.com/osx86-ijb/Dell-Latitude-3440-4th-Gen-Core-i3-4010U-1.7GHz-macOS/assets/67184728/17076060-a05f-4d62-9d56-c53bfaa27d1a)

## macOS Catalina 10.15.7 (19H2026)
![Screen Shot 2023-09-02 at 8 01 35 AM](https://github.com/osx86-ijb/Dell-Latitude-3440-4th-Gen-Core-i3-4010U-1.7GHz-macOS/assets/67184728/ca9ae149-abd6-4fdb-8fdc-004a484ceed0)

## macOS Big Sur 11.7.9 (20G1426)
<img width="1680" alt="Screen Shot 2023-09-01 at 6 51 58 PM" src="https://github.com/osx86-ijb/Dell-Latitude-3440-4th-Gen-Core-i3-4010U-1.7GHz-macOS/assets/67184728/a3eefb6f-7872-47fb-9e2b-e82ef9f94387">

## macOS Monterey 12.6.8 (21G725)
<img width="1680" alt="Screen Shot 2023-09-01 at 4 21 26 PM" src="https://github.com/osx86-ijb/Dell-Latitude-3440-4th-Gen-Core-i3-4010U-1.7GHz-macOS/assets/67184728/c194e887-2058-48a5-b8fe-87dd0b2fe168">

## macOS Ventura 13.5.2 (22G91)
<img width="1680" alt="Screenshot 2023-09-14 at 8 18 24 PM" src="https://github.com/osx86-ijb/Dell-Latitude-3440-4th-Gen-Core-i3-4010U-1.7GHz-macOS/assets/67184728/d6457c41-8e75-4509-bae0-7ba5350f67a6">

## macOS Sonoma 14.0 (23A339)
<img width="1680" alt="Screenshot 2023-09-14 at 7 03 18 PM" src="https://github.com/osx86-ijb/Dell-Latitude-3440-4th-Gen-Core-i3-4010U-1.7GHz-macOS/assets/67184728/4704b0dc-39b3-481d-9596-d43e44878336">


#### THESE ARE PUT IN PLACE FOR USE WITH EACH VERSION OF MACOS AND HAVE BEEN SET UP ACCORDINGLY.
#### MINKERNEL AND MAXKERNEL ARE IN USE FOR KEXTS IN CONFIG.PLIST TO ENSURE COMPATABILITY AND AS A FAILSAFE MEASURE FOR WHEN USERS DECIDE TO ATTEMPT TO MISMATCH BRANCHES WITH THEIR CHOSEN VERSIONS OF THE OS.

### Everything is working except for:
- Sleep instant wake / not sleeping properly
- VGA (as this has never been supported, and never will be unless you hand key in the support for it yourself)

# mhrv-rs-VPN-proxy-sni
A app for iranian people that can connect to the internet for free! 

more code will come just wait for 2-4 days 


یه اپلیکیشن برای ایرانی های که بتونن به اینترنت وصل بشن !

بقیه کد ها در چند روز اینده میاد منتظر باشین 




توضیحات به دو زبان نوشته شده اول فارسی سپس اینگیلیسی
the detail is writing in tow languges first persian and then english


هشدار برای اطمینان از کار کردن ابتدا تمام دستور عمل رو بخونید سپس اقدام کنید 

این اپلیکیشن یه صورت خارقعالده ای کار میکنه :

ابتدا فایل زیپ این سورس کد رو دانلود کنید و سپس توی یک پوشه ی مشخص اکسترکت هیر کنید 

بعد 4 فایل برایتان باز میشود 

اگر برای دفعه ی اول این فایل را دارید و تا به حال بازش نکرده اید فایل run.bat را اجرا کنید یکم طول میکشد سپس یک اپلیکیشن با منوی سیاه با میاید 



ان اپلیکیشن اپلیکیشن پروکسی شما هست این اپ را در بخش mode  روی direct(no relay) بزارید تا بدون استافده از deployment id  و AUTH key به سرور های گوگل متصل شوید البته فقط گوگل 


سپس شما باید در تنظیمات سیستم پروکسیتان را فعال کنید :

در ویندوز 10 : setting => network and internet => proxy => set up proxy server 

 توجه داشته باشید که باید در بخش ip adress  عدد 127.0.0.1 نوشته شده و در بخش port باید عدد 8085 نوشته شده باشد 

در بخش زیرین این عبارت باید باشد :

```

localhost;127.*;10.*;172.16.*;172.17.*;172.18.*;172.19.*;172.20.*;172.21.*;172.22.*;172.23.*;172.24.*;172.25.*;172.26.*;172.27.*;172.28.*;172.29.*;172.30.*;172.31.*;192.168.*

```


  سپس همه ی پنجره ها را نبندین و مینی مایز کنید تا در دست و پا نباشد 

  ویندوز 11 : setting => internet => proxy => set up proxy 
  و همون کار های بالا با توضیحات را انجام دهید 

سپس روی گزینه ی استارت گزینه ی سبز کلیک کنید و میبینید که ران میشود 

سپس به سایت گوگل اپ اسکریپ بروید که اگر در گوگل بزنید scripy google  اولین سایتی را که بالا میاره بزنید این فقط سایت اپ اسکریت رو بالا میاره تا دیپلویمنت ایدی رو بسازید 

سپس بروید و فایل code.txt که در بخشی که فایل زیپ را اکسترکت بردارین و تمام محتوای اون فایل رو کپی کنید 

سپس در سایت گوگا اپ اسکریپت new project رو بزنید و در انجا یکسری کد هست پاک کنید و با کدی که قبلا کپی کردید جایگزین کنید 

کاری باید انجام دهید اینه که در قسمت :

```
const AUTH_KEY = "CHANGE_ME_TO_A_STRONG_SECRET";
```

بین کوتیشن در بخشی که نوشته CHANGE_ME_TO_A_STRONG_SECRET یه اعداد و رقم طولانی برای خد تایپ و زیاد مهم نیست چی باشد این پسوورد شماست بهتر است که تعداد رقم هایش زیاد باشد این را در یک جا نگه داریم این پسووردتان را 

سپس در قسمت نوار بالا گزینه ی ابی رنگ Deploy بزنید 
و سپس new deployment 

یک پنجره باز میشود یک کلمه ی select type  وجود دارد و روی ایکون چرخ دنده ی بقلش کیلیک کنید و بزارید روی web app

در بخش کناری دیسکریپشن نمیخدا و بخش web app رو روی ایمیل خودتان بگذارید 

بخش who can access را روی Anyone بزارید تا توانایی استفاده شدن داشته باشد 
 


سپس deploy گزینه ابی رو میزنید و دو عبارت میدهد اولین عبارت را کپی کنید و در کنار جایی که پسووردتان را کپی گردین بزارید چون بعدا با هر جفتشان کار داریم 


در اینجا یک پروسه ی احراز حویت نیاز است این را انجام دهید
اگر در صفحه ی احراز هویت ارور یا هرچیزی داد پس از چند بار رفرش کردن درست میشودپ
اگر هم درست نشد از مرورگر Edge ماکروسافت استفاده کنید 

همانطور که گفتم اولین عبارت را کپی کنید و نگه دارید


حال یک محدودیت وجود دارد هر دیپلویمنت ای دی 20.000 ریکوست میتواند بزند به همین دلیل پس از استافده هر دیپلویمنت ایدی 3-4 ساعت وصل هستید 

بهتر از 3-4 تا دیپلویمنت ایدی بگیرید با انجام همان کار هر دفعه یک دیپلومنت ایدی جدید میاید

لازم به ذکر است که چون این اپلیکیشن یا برنامه چون از سرور ها و سرویس های گوگل + لوکال هاست لپتاپ شما استفاده میکنه اگر سایت گوگل فیلتر شود ( که در حال حاضر نیست ) این اپ یا برنامه دیگر کار نمیکند ان وقت گروه ما روش جدیدی ارائه خواهد داد با حمایت های شما 

سپس در اپلیکیشنی که برایتان باز شد ( اپلیکیشن سیاه که اول باز شد ) ان را خاموش کنید و mode برنامه را روی app script  بگذارید 

حال در بخش app script در بخش AUTH_key پسوورد سیو شدتان را بگذارید و در بخش Deployment id دیپلویمنت ایدی را بگذارید ( اگر چند دویپلویمنت ایدی گرفتید همه را یکجا بزارید ) 


سپس روی گزینه ی save config بزنید و روشنش کنید و پروکسی شما بدون سرور بدون محدودیت حجم کاملا رایگان بدون دردسر فعال است و کار میکند 

حال به google chrome بروید و سایت های فیلتر را باز کنید و لذت ببرید 

*نکته ی بسیار مهم : اگر در مرورگر google chrome سایت ها را باز نکرد مرورگر را عوض کنید بهتر است از microsoft edge استفاده کنید 


و نکته ی دیگه این روش برای ویندوز بود جهت دانلود فایل های لینوکی و مک :

| You're on | Download this |
|---|---|
| Mac with Apple Silicon (M1 / M2 / M3 / M4 chip) | `mhrv-rs-macos-arm64-app.zip` |
| Mac with Intel chip | `mhrv-rs-macos-amd64-app.zip` |
| Windows | `mhrv-rs-windows-amd64.zip` |
| Linux (Ubuntu / Mint / Fedora / Debian / Arch) | `mhrv-rs-linux-amd64.tar.gz` |
| Android phone or tablet | `mhrv-rs-android-universal-v*.apk` |
| OpenWRT router or Alpine | `mhrv-rs-linux-musl-amd64.tar.gz` |

تمامی فایل ها در بخش اپلود هست

و برای اینکه درک بهتری از امنیت و ساهتارش داشته باشید :

```
   you  →  browser  →  mhrv-rs  ──┐
                                  │ ISP only sees:  www.google.com
                                  ▼
                          Google's network
                                  │
                                  ▼
              your free Apps Script  fetches  the real site
                                  │
                                  ▼
                Twitter / ChatGPT / blocked-site of your choice

```
امید واردم لذت برده باشید حمایت یادتون نره ❤



english :

Warning: To ensure proper functioning, read the entire instructions first, then proceed.
This application works incredibly:

First, download the zip file of this source code and then extract it into a specified folder.
Then, four files will open for you.

If this is your first time with this file and you haven’t opened it before, run the file run.bat. It may take a little time, then an application with a black menu will appear.

This application is your proxy application. Set it to mode on direct (no relay) to connect to Google servers without using the deployment ID and AUTH key, but only for Google.

Then, you need to enable your system proxy settings:

For Windows 10:

Go to: Settings => Network and Internet => Proxy => Set up proxy server.Make sure that in the IP Address field, the number 127.0.0.1 is written, and in the Port field, it should be 8085.

In the lower section, this should be included:

```
localhost;127.*;10.*;172.16.*;172.17.*;172.18.*;172.19.*;172.20.*;172.21.*;172.22.*;172.23.*;172.24.*;172.25.*;172.26.*;172.27.*;172.28.*;172.29.*;172.30.*;172.31.*;192.168.*
```


Then don’t close all the windows, minimize them so they are not in the way.
For Windows 11:

Go to: Settings => Internet => Proxy => Set up proxyPerform the same steps with the provided details.

Then click on the green option to start, and you will see that it runs.
Next, visit the Google Apps Script website, and if you search on Google for "Apps Script Google," click the first site that appears. This only brings up the Apps Script site to create a deployment ID.
Then, go and find the code.txt file where you extracted the zip file, and copy all its content.
Next, on the Google Apps Script site, click on New project and remove any existing code, replacing it with the code you copied earlier.
You need to do the following in the section:

```
const AUTH_KEY = "CHANGE_ME_TO_A_STRONG_SECRET";
```

Between the quotes where it says CHANGE_ME_TO_A_STRONG_SECRET, type a long number and letters for the password—it doesn’t matter too much what it is. This is your password, and it’s better for it to be lengthy. Keep this password in a safe place.
Then, in the top bar, click on the blue Deploy option, and then New deployment.
A window will open with the phrase Select type, click on the gear icon next to it and set it to Web app.
In the description section, you don’t need anything, and for the Web app, put your own email.
Set the Who can access section to Anyone so it can be used.
Then click the blue Deploy option. It will give you two phrases; copy the first one and place it next to where you copied your password because we will be working with both later.
Here, a verification process is required. Please complete it. If there’s an error or anything on the verification page, it will resolve itself after refreshing a few times. If it still doesn’t, use Microsoft Edge browser.
As I mentioned, copy the first phrase and keep it safe.
Now, there is a limitation: each deployment ID can make 20,000 requests. Therefore, after use, each deployment ID will remain connected for 3-4 hours.
It’s better to obtain 3-4 deployment IDs. Every time you do this, a new deployment ID will appear.
It’s worth mentioning that because this application uses Google servers and services + your laptop's localhost, if the Google site gets blocked (which it currently is not), this app or program will no longer work. In such a case, our group will provide a new method with your support.
Then, in the application that opened for you (the black application that opened first), turn it off and set the program mode to App Script.
Now, in the App Script section, place your saved password in the AUTH_key section, and put the deployment ID in the Deployment ID section (if you obtained multiple deployment IDs, place them all at once).
Then click the Save config option and turn it on. Your proxy will be active without a server, no volume limitations, completely free, and hassle-free.
Now, go to Google Chrome and open filtered sites and enjoy!


Very Important Note: If you can't open sites in the Google Chrome browser, try switching browsers. It’s better to use Microsoft Edge.


And another note: This method was for Windows; for downloading files for Linux and Mac:

| You're on | Download this |
|---|---|
| Mac with Apple Silicon (M1 / M2 / M3 / M4 chip) | `mhrv-rs-macos-arm64-app.zip` |
| Mac with Intel chip | `mhrv-rs-macos-amd64-app.zip` |
| Windows | `mhrv-rs-windows-amd64.zip` |
| Linux (Ubuntu / Mint / Fedora / Debian / Arch) | `mhrv-rs-linux-amd64.tar.gz` |
| Android phone or tablet | `mhrv-rs-android-universal-v*.apk` |
| OpenWRT router or Alpine | `mhrv-rs-linux-musl-amd64.tar.gz` |

and all files that i write in chart is here don't worry!



and this chart show structor:

```

   you  →  browser  →  mhrv-rs  ──┐
                                  │ ISP only sees:  www.google.com
                                  ▼
                          Google's network
                                  │
                                  ▼
              your free Apps Script  fetches  the real site
                                  │
                                  ▼
                Twitter / ChatGPT / blocked-site of your choice

```


have fun and support us for more






<h1><p align="center"><stronge>🌟سورس ربات تبچی🌟</stronge>

<h3 align="right"> <strong> کد های نصب</strong> ✨
<hr>
<br></h4>
<h6 dir="rtl"></h6>
<pre>
<span>git clone https://github.com/cracker1375/tabchi.git && cd tabchi && chmod +x install && chmod 777 screen && chmod +x start && ./install && ./start</span>
</pre>
<h4 dir="rtl"> 1️⃣حالا از شما شماره میخواد، شماره ربات و کد تایید را وارد کنید.
<h4 dir="rtl"> 2️⃣در ادامه باید وارد ربات @botfather شوید و یک ربات برای خود درست کنید و توکن ربات را در فایل apistart در لاین 4 وارد کنید
<h4 dir="rtl"> 3️⃣مرحله بعدی باید ایدی عددی ربات api که در اول توکن قرار دارد را در فایل های زیر در لاین های دوم و سوم جایگزین ایدی موجود کنید

<h4 dir="rtl"> 🔹tabchi/bot/api.lua

<h4 dir="rtl"> 🔹tabchi/bot/tabchi.lua
<h4 dir="rtl">در ادامه باید ایدی عددی سودوی ربات (کسی که تبچی ها را مدیریت می کند) را در فایل های زیر در لاین های 16 و 17 ست کنید)

<h4 dir="rtl"> 🔹برای پیدا کردن ایدی عددی خودتان @userinfobot را داخل اکانت اصلی خود استارت کنید

<h4 dir="rtl"> 🔹tabchi/bot/api.lua

<h4 dir="rtl"> 🔹tabchi/bot/tabchi.lua           
<h4 dir="rtl"> 4️⃣در ادامه باید ربات خود را لانچ کنیم. یک ترمینال جدید باز کنید و دستور زیر را ارسال کنید
<pre>
<span>cd tabchi && screen ./screen</span>
</pre>
<h4 dir="rtl"> خوب حالا ترمینال فعلی را ببندید و یک ترمینال جدید دیگر باز کنید و دستور زیر را ارسال کنید
<pre>
<span>cd tabchi && nohup ./apistart</span>
</pre>
<h4 dir="rtl"> ⚠️نکته مهم⚠️
<h4 dir="rtl"> دقت کنید ربات api همان رباتی که داخل botfather ساختید را داخل اکانت اصلی و اکانت تب چی استارت کنید
<h4 dir="rtl">ابتدا باید عملیات setapi را انجام بدید برای انجام این کار دستور setapi token را در پی وی شماره تبچی خود ارسال کنید (دقت کنید به جای کلمه token توکن ربات خود را قرار دهید)


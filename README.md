# Awesome Print

### **What problem does Awesome Print solve ??**

Rails objects can get pretty dense and hard to read when inspecting in the console. <br> 
Awesome print solves this problem by prettifying the output.
<br>

### **How do you use it in a rails app ??**
```
#Gemfile

gem "awesome_print", require:"ap"
```
   Make sure to include the require:"ap" option
 <br>
 <br>

```
#Terminal

bundle install
rails s
```
Do "bundle install" in your terminal and restart the rails console.
<br>
<br>

## you are ready to use Awesome Print !!!

<br>
<br>
<br>

# Before using Awesome Print

```
#Terminal

rails c
City.all
```

![](http://postfiles14.naver.net/MjAxNzAxMzFfMjQg/MDAxNDg1ODE0NTM2Mjk1.r4ocxiJZQ8WaOrOFUVokfSfzHr3G2tGR7-xhhgDx-uog.4gHoewweknw4wCjlnd_oEM5S0sdmhho6ShtYObj8CEEg.PNG.nosugars/before.png?type=w580)

It is quite difficult to see each data.
<br>
<br>

# After using Awesome Print

```
#Terminal

rails c
ap City.all
```

![](http://postfiles14.naver.net/MjAxNzAxMzFfMjY1/MDAxNDg1ODE0NTQ0MTE1.zTfSVmk13H8kiIUYZbk51d-EqgTaxKkp9xrBGnatTX4g.U4JKJphid0HmR7W0hQFIh1jrfj0lpfHnOGcLRs2kpFwg.PNG.nosugars/after.png?type=w580)

**Data is beautified !!!! **

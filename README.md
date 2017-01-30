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

![](http://postfiles13.naver.net/MjAxNzAxMzFfMTk1/MDAxNDg1ODE1NDQ4NjE2.naI4nbsOSTvb8CRtfNGoEc80nynAAu7NDNWd0fhnEfgg.3F6Oh2khX7MV1PPTYdmSMieDWheiPIoUkrQnK4XpZLMg.PNG.nosugars/before.png?type=w3)

It is quite difficult to see each data.
<br>
<br>

# After using Awesome Print

```
#Terminal

rails c
ap City.all
```
Don't forget to put ap.

![](http://postfiles16.naver.net/MjAxNzAxMzFfNTcg/MDAxNDg1ODE1NDQ5NDA2.NiD0Ix-MWSEeHrm8ixJnrK8pWSGDkQI_GBSEt1SlNAwg.AsWwBUT1ddNg5DlV856DUK4nrM2nBrAn9GIVJxnYePcg.PNG.nosugars/after.png?type=w3)

**Data is beautified !!!!**

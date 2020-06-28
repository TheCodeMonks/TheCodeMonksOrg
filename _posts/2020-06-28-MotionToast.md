---
layout: post
title:  "[Android] Motion Toast - A Beautiful Toast Library for Android Kotlin 🤩🔥 "
author: sanjay
categories: [ android-library, android ]
image: assets/images/motiontoast.png
beforetoc: "A Beautiful Multipurpose Motion Toast Library in Android using Kotlin 😍"
toc: true
---
A Beautiful Multipurpose Motion Toast Library in Android using Kotlin 😍

![GitHub Cards Preview](https://github.com/Spikeysanju/Video_templates/raw/master/Github%20Card.png)

## Preview - Motion Toast 🌟 
![gif](https://github.com/Spikeysanju/Video_templates/raw/master/Motion%20Toast.gif)

## Preview - Color Motion Toast 🌈
![gif](https://github.com/Spikeysanju/Video_templates/raw/master/Toast%20Types-5.png)

## Preview - Dark Toast 🌈
![gif](https://github.com/Spikeysanju/Video_templates/raw/master/Dark%20Toast.png)

## Preview - Dark Color Toast 🌈
![gif](https://github.com/Spikeysanju/Video_templates/raw/master/Dark%20Color%20Toast.png)


# Types of Toast Style ❤️


<table style="width:100%">
  <tr>
    <th>1. Motion Toast </th>
    <th>2. Color Motion Toast</th> 
    <th>3. Dark Toast </th>
    <th>4. Dark Color Toast</th> 
  </tr>
  <tr>
    <td><img src = "https://github.com/Spikeysanju/Video_templates/raw/master/Toast%20Types-3.png"/></td> 
    <td><img src = "https://github.com/Spikeysanju/Video_templates/raw/master/Toast%20Types-5.png"/></td>
    <td><img src = "https://github.com/Spikeysanju/Video_templates/raw/master/Dark%20Toast.png"/></td> 
    <td><img src = "https://github.com/Spikeysanju/Video_templates/raw/master/Dark%20Color%20Toast.png"/></td> 
   
  </tr>
</table>

## About

A Beautiful Multipurpose Motion Toast Library in Android using Kotlin. 

## Dependency Project Level

Step 1. Add the JitPack repository to your build file

Add it in your root build.gradle at the end of repositories:



```javascript
	allprojects {
		repositories {
			...
			maven { url 'https://jitpack.io' }
		}
	}

```

## Dependency App Level

Add dependency in your app module

```javascript
	dependencies {
	        implementation 'com.github.Spikeysanju:MotionToast:1.3.2' 
	}

```
## Five Toast Types 🖐🏼
```javascript
        1. TOAST_SUCCESS
        2. TOAST_ERROR
        3. TOAST_WARNING
        4. TOAST_INFO
        5. TOAST_DELETE
```

## Toast Duration ⌛️ 
```javascript
        1. LONG_DURATION // 4 Seconds
        2. SHORT_DURATION // 2 Seconds
       
```

## Usage 

# Sample Code for - Motion Toast 🌟 

### Success Toast
```javascript
 MotionToast.createToast(this,"Upload Completed!",
                MotionToast.TOAST_SUCCESS,
                MotionToast.GRAVITY_BOTTOM,
                MotionToast.LONG_DURATION,
                ResourcesCompat.getFont(this,R.font.helvetica_regular))
                
```

### Error Toast
```javascript
 MotionToast.createToast(this,"Profile Update Failed!",
                    MotionToast.TOAST_ERROR,
                    MotionToast.GRAVITY_BOTTOM,
                    MotionToast.LONG_DURATION,
                    ResourcesCompat.getFont(this,R.font.helvetica_regular))  
```
### Warning Toast
```javascript
MotionToast.createToast(this,"Please fill all the details!",
                    MotionToast.TOAST_WARNING,
                    MotionToast.GRAVITY_BOTTOM,
                    MotionToast.LONG_DURATION,
                    ResourcesCompat.getFont(this,R.font.helvetica_regular))  

        
```

### Info Toast
```javascript
       MotionToast.createToast(this,"This is information toast!",
                    MotionToast.TOAST_INFO,
                    MotionToast.GRAVITY_BOTTOM,
                    MotionToast.LONG_DURATION,
                    ResourcesCompat.getFont(this,R.font.helvetica_regular))  

```
### Delete Toast
```javascript
       MotionToast.createToast(this,"Delete all history!",
                    MotionToast.TOAST_DELETE,
                    MotionToast.GRAVITY_BOTTOM,
                    MotionToast.LONG_DURATION,
                    ResourcesCompat.getFont(this,R.font.helvetica_regular))  

```

# Sample Code for - Color Motion Toast 🌈

### Success Toast
```javascript
 MotionToast.createColorToast(this,"Upload Completed!",
                MotionToast.TOAST_SUCCESS,
                MotionToast.GRAVITY_BOTTOM,
                MotionToast.LONG_DURATION,
                ResourcesCompat.getFont(this,R.font.helvetica_regular))
                
```

### Error Toast
```javascript
 MotionToast.createColorToast(this,"Profile Update Failed!",
                    MotionToast.TOAST_ERROR,
                    MotionToast.GRAVITY_BOTTOM,
                    MotionToast.LONG_DURATION,
                    ResourcesCompat.getFont(this,R.font.helvetica_regular))  
```
### Warning Toast
```javascript
MotionToast.createColorToast(this,"Please fill all the details!",
                    MotionToast.TOAST_WARNING,
                    MotionToast.GRAVITY_BOTTOM,
                    MotionToast.LONG_DURATION,
                    ResourcesCompat.getFont(this,R.font.helvetica_regular))  

        
```

### Info Toast
```javascript
       MotionToast.createColorToast(this,"This is information toast!",
                    MotionToast.TOAST_INFO,
                    MotionToast.GRAVITY_BOTTOM,
                    MotionToast.LONG_DURATION,
                    ResourcesCompat.getFont(this,R.font.helvetica_regular))  

```
### Delete Toast
```javascript
       MotionToast.createColorToast(this,"Delete all history!",
                    MotionToast.TOAST_DELETE,
                    MotionToast.GRAVITY_BOTTOM,
                    MotionToast.LONG_DURATION,
                    ResourcesCompat.getFont(this,R.font.helvetica_regular))  

```

# Sample Code for - Dark Toast 🌚🖤 

### Success Toast
```javascript
 MotionToast.darkToast(this,"Upload Completed!",
                MotionToast.TOAST_SUCCESS,
                MotionToast.GRAVITY_BOTTOM,
                MotionToast.LONG_DURATION,
                ResourcesCompat.getFont(this,R.font.helvetica_regular))
                
```

### Error Toast
```javascript
 MotionToast.darkToast(this,"Profile Update Failed!",
                    MotionToast.TOAST_ERROR,
                    MotionToast.GRAVITY_BOTTOM,
                    MotionToast.LONG_DURATION,
                    ResourcesCompat.getFont(this,R.font.helvetica_regular))  
```
### Warning Toast
```javascript
MotionToast.darkToast(this,"Please fill all the details!",
                    MotionToast.TOAST_WARNING,
                    MotionToast.GRAVITY_BOTTOM,
                    MotionToast.LONG_DURATION,
                    ResourcesCompat.getFont(this,R.font.helvetica_regular))  

        
```

### Info Toast
```javascript
       MotionToast.darkToast(this,"This is information toast!",
                    MotionToast.TOAST_INFO,
                    MotionToast.GRAVITY_BOTTOM,
                    MotionToast.LONG_DURATION,
                    ResourcesCompat.getFont(this,R.font.helvetica_regular))  

```
### Delete Toast
```javascript
       MotionToast.darkToast(this,"Delete all history!",
                    MotionToast.TOAST_DELETE,
                    MotionToast.GRAVITY_BOTTOM,
                    MotionToast.LONG_DURATION,
                    ResourcesCompat.getFont(this,R.font.helvetica_regular))  

```

# Sample Code for - Dark Color Toast 🌚🖤🌈

### Success Toast
```javascript
 MotionToast.darkColorToast(this,"Upload Completed!",
                MotionToast.TOAST_SUCCESS,
                MotionToast.GRAVITY_BOTTOM,
                MotionToast.LONG_DURATION,
                ResourcesCompat.getFont(this,R.font.helvetica_regular))
                
```

### Error Toast
```javascript
 MotionToast.darkColorToast(this,"Profile Update Failed!",
                    MotionToast.TOAST_ERROR,
                    MotionToast.GRAVITY_BOTTOM,
                    MotionToast.LONG_DURATION,
                    ResourcesCompat.getFont(this,R.font.helvetica_regular))  
```
### Warning Toast
```javascript
MotionToast.darkColorToast(this,"Please fill all the details!",
                    MotionToast.TOAST_WARNING,
                    MotionToast.GRAVITY_BOTTOM,
                    MotionToast.LONG_DURATION,
                    ResourcesCompat.getFont(this,R.font.helvetica_regular))  

        
```

### Info Toast
```javascript
       MotionToast.darkColorToast(this,"This is information toast!",
                    MotionToast.TOAST_INFO,
                    MotionToast.GRAVITY_BOTTOM,
                    MotionToast.LONG_DURATION,
                    ResourcesCompat.getFont(this,R.font.helvetica_regular))  

```
### Delete Toast
```javascript
       MotionToast.darkColorToast(this,"Delete all history!",
                    MotionToast.TOAST_DELETE,
                    MotionToast.GRAVITY_BOTTOM,
                    MotionToast.LONG_DURATION,
                    ResourcesCompat.getFont(this,R.font.helvetica_regular))  

```

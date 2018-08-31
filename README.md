# Unity-2018-Cookbook-Second-Edition
Unity 2018 Cookbook, Second Edition, published by Packt
# Book Name

<a href="Packt UTM URL of the Book"><img src="Cover Image URL of the Book" alt="Book Name" height="256px" align="right"></a>

This is the code repository for [Book Name](Packt UTM URL of the Book), published by Packt.

**Over 160 recipes to take your 2D and 3D game and virtual reality development to the next level**

## What is this book about?
First Paragraph from the Long Description
With the help of the Unity 2018 Cookbook, you’ll discover how to make the most of the UI system, learn to work with external resources and files, and understand how to animate both 2D and 3D characters and game scene objects using Unity's Mecanim animation toolsets.

This book covers the following exciting features: <First 5 What you'll learn points>
* Get creative with Unity’s shaders and learn to build your own shaders with the new Shader Graph tool
* Create a text and image character dialog with the free Fungus Unity plugin
* Explore new features integrated into Unity 2018, including TextMesh Pro and ProBuilder
* Master Unity audio, including ducking, reverbing, and matching pitch to animation speeds
* Work with the new Cinemachine and timeline to intelligently control camera movements

If you feel this book is for you, get your [copy](https://www.amazon.com/dp/1788471903) today!

<a href="https://www.packtpub.com/?utm_source=github&utm_medium=banner&utm_campaign=GitHubBanner"><img src="https://raw.githubusercontent.com/PacktPublishing/GitHub/master/GitHub.png" 
alt="https://www.packtpub.com/" border="5" /></a>


## Instructions and Navigations
All of the code is organized into folders. For example, Chapter01.

The code will look like the following:
```
using UnityEngine; 
using System.Collections; 

public class ScrollZ : MonoBehaviour { 
  public float scrollSpeed = 20; 

  void Update () { 
    Vector3 pos = transform.position; 
    Vector3 localVectorUp = transform.TransformDirection(0,1,0); 
    pos += localVectorUp * scrollSpeed * Time.deltaTime; 
    transform.position = pos; 
  } 
} 
```

**Following is what you need for this book:**
Copy and paste the Audience section from the EPIC.

With the following software and hardware list you can run all code files present in the book (Chapter 1-15).

### Software and Hardware List

| Chapter  | Software required                   | OS required                        |
| -------- | ------------------------------------| -----------------------------------|
| 1-4,6-19 | Unity 2018.1 or later               | Windows, Mac OS X, and Linux (Any) |
| 5        | Unity 2018.1 or lagter +            |                                    |
|          | an image editing application        |                                    |
|          | such as GIMP                        | Windows, Mac OS X, and Linux (Any) |



We also provide a PDF file that has color images of the screenshots/diagrams used in this book. [Click here to download it](Graphics Bundle Link).

## Code in Action

Click on the following link to see the Code in Action:

[Placeholder link](www.youtube.com/URL)

### Related products <Other books you may enjoy>
* Linux: Powerful Server Administration [[Packt]](https://www.packtpub.com/networking-and-servers/linux-powerful-server-administration?utm_source=github&utm_medium=repository&utm_campaign=9781788293778) [[Amazon]](https://www.amazon.com/dp/1788293770)

* Linux Device Drivers Development [[Packt]](https://www.packtpub.com/networking-and-servers/linux-device-drivers-development?utm_source=github&utm_medium=repository&utm_campaign=9781785280009) [[Amazon]](https://www.amazon.com/dp/1788293770)

## Get to Know the Author(s)
**Author Name**
Bio




## Other books by the authors
* [Mastering Linux Network Administration](https://www.packtpub.com/networking-and-servers/mastering-linux-network-administration?utm_source=github&utm_medium=repository&utm_campaign=9781784399597)
* [Linux Mint Essentials](https://www.packtpub.com/networking-and-servers/linux-mint-essentials?utm_source=github&utm_medium=repository&utm_campaign=9781782168157)

### Suggestions and Feedback
[Click here](https://docs.google.com/forms/d/e/1FAIpQLSdy7dATC6QmEL81FIUuymZ0Wy9vH1jHkvpY57OiMeKGqib_Ow/viewform) if you have any feedback or suggestions.

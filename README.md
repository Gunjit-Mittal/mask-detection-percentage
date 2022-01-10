<!-- This is the markdown template for the final project of the Building AI course, 
created by Reaktor Innovations and University of Helsinki. 
Copy the template, paste it to your GitHub README and edit! -->

#  Mask Detection Percentage
## Final project for the Building AI course

## Summary
My idea is about taking a quick 360 degree photo anywhere and process it through AI based image processing in order to calculate the percentage of people wearing face masks. This concept can be helpful for government authorities to quickly check how well the public is following the rules. 
## Background
This is how you make a list, if you need one:
* With this idea I plan on helping the government better tackle the covid-19 situation. As having even a vague guess about the percentage of people following the rules can get hard in public concerts or political rally's.Also these are probably the prime location for a covid boom.
* Knowing the approximate percentage of people wearing the masks it can be possible to further compute how risky is the concert or event. This can occur quite frequently as if applied worldwide such events occur at a huge scale.
* As of personal motivation i feel it is very bad on people of my region to very much disobey the rules set by the goevrnment and roam freely without masks no matter how serious the situation is.Also helping to fight covid is something we should all do.
* It will be really interesting to know how well the people follow the rules knowing they will surely be caught and a lower percentage of masks might even result in cancellation of the event of their favoutite person.Also the implementation is a liitle bit like voting where we all know that one vote can't change the result but each vote will change the result
## How is it used?
* First of all we need a good quality 360 degree camera to picture the surrounding like this 
 and then all we need is a specialized face detection algorithm which can track all sorts of masks like face shields, colourful cloth masks, and standard masks as well. Also we need to track people not wearing any sort of masks.<img src="https://content.fortune.com/wp-content/uploads/2017/04/x24_x6_009_b.png" width="300">
* Once we have a clear idea of what percentage of people were masked at a particular event then we can compute the danger and in case it is high we might as well cancel any other similar event.
* As to what kind of environments we can use this it will totally depend on how well the image recognition algorithm is trained and how much resolution our camera can capture under different lighting conditions
* The users for this particular application will be of course the local police authorities who will report the data to the state governments in order to take action.
* Also if we can get a good mounting spot then we can just mount the camera on a busy street and calculate real time data and hence achieve better approximations
Since it will be used by the government we need to make sure it is pretty accurate as we don't want to give misleading information to the governments. Also once the photos are captured it wont be problematic to process those later as we probably have some maintainence time on the event location. For the street cameras we can probably increase computing power or let the images be of lower resolution as streets are much more emptier than events(especially concerts)
## Data sources and AI methods
* For this particular application we can surely have something pretrained with a lot of data of people wearing different kinds of masks and also people not wearing masks.Also we need some kind of algorithm to predict the danger at a particular ask percentage.This can be done by considering the scientifict experiments which suggest how effective a mask can be against covid-19.I once saw that a mask could only ever contain about 50% of the virus and is therby 50% effective(Though this was just something on internet and i am not sure about this, but definitely there will be more rigid tests and the results of those can help us compute the danger).Another potential source may be government information about any previous instances.
* We will require a well trained image recognition algorithm and an AI that will learn from the results and become better at predicting them 
## Challenges
There are several problems which i just assumed to be non existent till now like : -
* Not having good enough hardware(both to capture and compute)
* People wearing masks sometimes but not all times
* People not wearing masks properly. 
* Capturing everyone in very jam packed concerts where it is impossible to even see everyone and also the fact that they are not stable and might be jumping around continuously
* Very harsh conditions like night time and people attending concerts with flash turned on on their phones
## What next?
* Some of the above said challenges can be solved with more training data and time while some may require elaborate techniques like to solve moving people issue we can just take a video(if possible) and then process it to get some godd image upon which our algorithm can work
* Another feature that can be implemented is checking for social distancing by calculating distance between two people


## Acknowledgments
I would like to thank Reaktor and The University of Helsinki for providing me with such a nice course and the fellow participants surfing whose ideas this wonderful idea struck me.


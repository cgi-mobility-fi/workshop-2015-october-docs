Mobilog DevDay 1: lessons learned
=================================

Lessons learned / conclusions / what to do next time.

Infrastructure
--------------

* Use a physical switch and cables instead of relying on wifi
* Prepare enough extension cords so that everyone can plug his/her laptop to power outlet socket
* Use mobility team's old projector that worked well instead of relying on the shaky one in the meeting room

Development
-----------

* Distribute VirtualBox virtual machine images to participants on USB sticks so that everyone can follow along without technical obstacles (as suggested in the original LOCC announcement, thanks for bringing this up, Niklas)
	* We will use Xubuntu Linux, as Tanel did - it is a slim but modern and fully functional Linux desktop distribution based on Ubuntu Linux
	* Even better, use Vagrant or Otto to setup everything with scripting? This will be slow though.
* Define the functionality of the applications we build with a clear spec with user stories and acceptance criteria so that everyone can understand what we want to achieve (thanks for bringing this up, Saara)
	* Maybe even start with this - present the goal and roadmap at the start of the presentation.
	* Would have been nice to play through the actual messaging scenarios with TryRabbitMQ.com.
	* Similarly, having UI mockups would be helpful in other applications we build in the future.
	* However, we should always experiment with the different alternative technologies for achieving our goals first - purely from technical perspective, so that we understand what tools we can use
* DevDay is a good occasion to try out new tools like Gradle instead of Maven etc.
* As there is some switching overhead, let people sit behind the shared computer for 20 minutes (or even 30 minutes).
* Keep working on the shared screen on the wall to practice consensus-reaching and pair programming navigation/driving skills. But also encourage everyone to try out things on their own.
	* However, people should experiment in their own laptops and share the results on screen with Google Hangouts.
* Balance between theory and practice - having a good introduction is especially important, but having two of these is perhaps less good than having just one and trying out all the topics covered in code by practicing.
	* Consider preparing the same topic so that two people work together
	* Tanel mentions that combining microservices and websockets into one project would have been great.
* Topics, code and infrastructure should be properly prepared so that there is no overhead on mundane hassle with environments. Push code to GitHub, prepare servers and credentials. Margus did this very well with RabbitMQ.
* Don't get stuck with technical roadblocks. If we get stuck, we waste time and lose the opportunity to deal with interesting stuff.
	* We didn't have many problems generally, but for example Tanel had problems with connecting to RabbitMq from Node.js - this was not a general roadblock though.

Paavo's feedback:

*For me it seems to be a necessary event we should organize regularly. In addition to covering new technologies, it gives the team also common understanding about nice and clean code. Seeing coding style on a big screen brought up some questions about coding conventions, which should be common in the team – and the DevDay was a great opportunity to discuss it.*

*Overall I got the impression that less theory and more hands-on coding is better. It was lots of fun overall.*

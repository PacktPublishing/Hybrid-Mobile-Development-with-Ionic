# Hybrid Mobile Development with Ionic
This is the code repository for [Hybrid Mobile Development with Ionic](https://www.packtpub.com/application-development/hybrid-mobile-development-ionic?utm_source=github&utm_medium=repository&utm_content=9781785286056), published by Packt. It contains all the supporting project files necessary to work through the book from start to finish.

## About the Book
This book will help you to develop a complete, professional and quality mobile application with Ionic Framework. You will start the journey by learning to configure, customize, and migrate Ionic 1x to 3x. Then, you will move on to Ionic 3 components and see how you can customize them according to your applications. You will also implement various native plugins and integrate them with Ionic and Ionic Cloud services to use them optimally in your application. By this time, you will be able to create a full-fledged e-commerce application. Next, you will master authorization, authentication, and security techniques in Ionic 3 to ensure that your application and data are secure. Further, you will integrate the backend services such as Firebase and the Cordova iBeacon plugin in your application. Lastly, you will be looking into Progressive Web Applications and its support with Ionic, with a demonstration of an offline-first application.

## Instructions and Navigation
All of the code is organized into folders. The commands and instructions will look like the following:

     // Angular & Ionic 1

       angular.module('wedding.controllers', [])
         .controller('LoginCtrl',
        function($scope, CategoryService) {
			   // controller function and DI of CategoryService
         }
     );

    // Angular 4 & Ionic 3

     import {Component} from '@angular/core';
     import {NavController} from 'ionic-angular';

      @Component({
     templateUrl: 'build/pages/catalog/categories.html'
    })
     export class CategoryPage {
    // DI of NavController for navigation
     constructor(private navCtrl: NavController) {
      this.nav = navCtrl;
     }
    }



## Related products:
* [Beginning Ionic Hybrid Application Development [Video]](https://www.packtpub.com/web-development/beginning-ionic-hybrid-application-development-video?utm_source=github&utm_medium=repository&utm_content=9781785284465)
* [Hybrid Cloud Management with Red Hat CloudForms](https://www.packtpub.com/virtualization-and-cloud/hybrid-cloud-management-red-hat-cloudforms?utm_source=github&utm_medium=repository&utm_content=9781785283574)
* [Getting Started with Ionic](https://www.packtpub.com/application-development/getting-started-ionic?utm_source=github&utm_medium=repository&utm_content=9781784390570)

### Suggestions and Feedback
[Click here](https://docs.google.com/forms/d/e/1FAIpQLSe5qwunkGf6PUvzPirPDtuy1Du5Rlzew23UBp2S-P3wB-GcwQ/viewform) if you have any feedback or suggestions. 
### Download a free PDF

 <i>If you have already purchased a print or Kindle version of this book, you can get a DRM-free PDF version at no cost.<br>Simply click on the link to download a free PDF copy of this book.</i>
<p align="center"> <a href="https://packt.link/free-ebook/9781785286056">https://packt.link/free-ebook/9781785286056 </a> </p>
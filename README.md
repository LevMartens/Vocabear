## About The Project

Vocabex is native IOS app that allows you to scan any page and filter out the most commonly used English words in order to help improve your English vocabulary. The scanner comes from the Vision framework. 
Whenever a scan is made vision will read the page from the scan/photograph, then the page will be filtered through and you'll be left with the uncommon words that you can save in the app and study.

The words that will be filtered are: the 5000 most common used words, 4000 common names, numbers, and close to 20.000 word forms derived from the 5000 most common words. 

Available on Apple Appstore.

### Build With
* Swift
* Xcode 
* Cocoa Pods
* MVC 
* Core Data
* Cloud Firestore
* Vision
* Multithreading
* Observers

## Usage
<img width="200" height="400" src="https://user-images.githubusercontent.com/73681740/110424610-2f133f00-80f7-11eb-8ade-448028b07b0f.jpg"  />  &nbsp;&nbsp;&nbsp;&nbsp; <img width="200" height="400" src="https://user-images.githubusercontent.com/73681740/110424663-3e928800-80f7-11eb-9505-04b0f9d9feef.jpg"  /> &nbsp;&nbsp;&nbsp;&nbsp; <img width="200" height="400" src="https://user-images.githubusercontent.com/73681740/110424697-4eaa6780-80f7-11eb-9f86-be4658835e38.jpg"  /> &nbsp;&nbsp;&nbsp;&nbsp; <img width="200" height="400" src="https://user-images.githubusercontent.com/73681740/110424720-58cc6600-80f7-11eb-8d88-703b1a82148e.jpg"  />







The words that will be filtered out are stored in Firebase FireStore and fetched on startup. 

After the scan completes, the words are presented and the user can choose to save the word, the words get saved in CoreData.

### The Future
I am working on incorporating added features including: word definitions, word difficulty levels, notes and word favoriting, a personalised filter as well as a personalised English level tracker.

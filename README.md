## Feed Reader Testing Project

Sixth project from the Front-End Web Developer Nanodegree in <a href="https://www.udacity.com" target="_blank">Udacity</a>:
<br>
created number of tests against a pre-existing Javascript testing framework **Jasmine**, to test the underlying business logic of the application as well as the event handling and DOM manipulation.

### To run the application

[Project Repo](https://github.com/markchen555/Feed-Reader-Testing-Project)

Fork a copy from my github or download the repository on your computer, unzip it and open `index.html` in your browser to see the working tests. See detail in `../jasmine/spec/feedreader.js`. 

---

### Tests implemented

- `RSS Feeds: have URL` loops through each feed and ensures it has a URL defined and that the URL is not empty.
- `RSS Feeds: have name` loops through each feed and ensures it has a name defined and that the name is not empy.
- `The menu: is hidden by default` ensures the menu element is hidden by default.
- `The menu: changes visibility` ensures the menu changes visibility when the menu icon is clicked. The test also excepts the menu to display when clicked and to hide when clicked again.
- `Initial Entries: has an .entry element after loading` ensures that, when the loadFeed function is called and completes its work, there is at least a single .entry element within the .feed container. 
- `New Feed Selection: changes the content when new feed is loaded` ensures that, when a new feed is loaded by the loadFeed function,  the content actually changes. 

---

### Udacity's instructions

In this project you are given a web-based application that reads RSS feeds. The original developers of this application clearly saw the value in testing, they've already included [Jasmine](http://jasmine.github.io/) and even started writing their first test suite! Unfortunately, they decided to move on to start their own company and we're now left with an application with an incomplete test suite. That's where you come in.

---

### Reference

[Jasmine 2.1 Documentation](https://jasmine.github.io/2.1/introduction.html)

---

### License

The project is licensed under the [MIT license](license.txt).

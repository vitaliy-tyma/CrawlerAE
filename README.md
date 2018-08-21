# CrawlerAE
Intro
Imagine that you are writing a simple web crawler that locates a user-selected element on a web site with frequently changing information. You regularly face an issue that the crawler fails to find the element after minor page updates. After some analysis you decided to make your analyzer tolerant to minor website changes so that you don’t have to update the code every time.

It would be best to view the attached HTML page, imagining that you need to find the “Everything OK” button on every page.

Requirements
Write a program that analyzes HTML and finds a specific element, even after changes, using a set of extracted attributes. We’ve prepared a sample HTML page (“original” below) and 4 simple difference cases: first, second, third, fourth (“diff-case” below) for you ( download as a single pack ). Please open the pages in browser to see what we mean by minor website changes. The target element that needs to be found by your program is the green “Everything OK” button. Any user can easily find this button visually, even when the site changes. Original contains a button with attribute id="make-everything-ok-button". This id is the only exact criteria, to find the target element in the input file.

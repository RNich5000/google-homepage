THE ODIN PROJECT: GOOGLE HOMEPAGE

30/01/2021
After trying to muck around with this website, I realised that despite doing a lot of online tutorials I still don't know what I'm doing. I'll come back to this project in a couple of days, once I've had some time to find and complete some more intermediary exercises to bridge my knowledge gaps.

28/01/2021
Here is the 'knowledge check' at the start of the project

===========
---Two ways to move a div around on the page
<div style="align: center;"></div>
or
???

---Stick a div onto the bottom or top of the page
vertical-align: top;
vertical-align: bottom;

---Identify the background color of an existing webpage
Either screenshot the image and check the colour in microsoft paint, or look at the source info in the web browser (find the element in the inspector and look at the colour code given). The second option will be more accurate, as sometimes you'll want to identify colour transitions etc.

---Grab the URL for an image from an existing webpage
-right click on the image you'd like to copy
-select 'copy image location'
-paste the URL in your chosen place

---Center an element horizontally
align: center;

---Identify three ways you can include your CSS styles in a page
1. add <style></style> tags at the top of the page, and add CSS to this section in conjunction with class and id tags
2. inject the CSS style directly into the HTML tag e.g. <div style="align: center;">Content</div>
3. not sure of a third one yet...

---Understand how to use classes and ids to target CSS at specific elements on the page
<style>
    .class {
        [class content goes here]
    }
    #id {
        [id styling goes here]
    }
</style>

<div class="class">Class content</div>
<div id="id">ID content</div>

---Build a very basic form (even if it doesn’t “go” anywhere)
<form action="">
    <input type="text" placeholder="text when the form is empty">
</form>
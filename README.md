# Simple-Ajax-Contact-Form-Using-jQuery-PHP

<li>creating a simple Ajax based Contact form using jQuery and PHP. </li>

<li> Why Ajax? because your visitors don’t have to reload the page in order to send you email, they can simply click send button and the email gets sent instantly before their eyes, so it’s just fantastic, no more page reloads! </li>

<li>  you should be able to pull it off if you are bit familiar with HTML, PHP and jQuery.</li>

<li> Have a look at the picture below, this is how our contact form going to look at the end.</li>

<li> We will have input fields as shown below, you can later add-remove other fields as per requirements of your HTML form.</li>

<br>

![nn](https://user-images.githubusercontent.com/12325386/29163657-b626479e-7def-11e7-9629-298f958acc09.JPG)



## Mark up

<li> Let’s start coding our contact page, we start by adding some input fields, you can review our code below. </li>

<li> A regular contact page contains name, email, phone and message fields, you may add other fields like check-boxes, radio buttons and select-boxes as per your requirements for the contact form. </li>


<li> If you look closely, you’ll realize that we didn’t wrap our fields with <FORM> tags here like in a typical HTML form. Since we are going to collect field values using jQuery .val(), we don’t really need a typical HTML form functionality here, all we need is some fields and a button to trigger jQuery code which will do the rest. </li>



## form style

<li> You can style your HTML form with CSS, you can either create a separate CSS or include the code within the <head></head> section of your page. </li>

<li> I personally use DevTool in chrome browser and Firebug in Firefox browser, these tools allow me to edit, debug, and monitor CSS, HTML and JavaScript in realtime. </li>

<li> If you haven’t used these tools before, you should definitely learn to use them, they are lifesavers. </li>


## jquery ajax

<li> Now it’s time to write some jQuery code for the contact page. </li>
<li> Before we start, make sure you have included jQuery library within the <HEAD> section of your HTML document, without it jQuery code doesn’t work. </li>

Right after $(document).ready(), we have $(“#submit_btn”).click(). If you notice the submit button ID in our HTML form above, you will realize that we are actually attaching the click event to the button. When a user clicks the button, the event gets triggered, executing all the code within it.


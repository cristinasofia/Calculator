<a href="https://o46rc.csb.app/">Demo</a>

<h1>Calculator</h1>
<p>Calculators are not only one of the most useful tools available, but they are also a great way to understand UI and event processing in an application. This app is a calculator that supports basic arithmetic calculations on integers.</p>
<h2>User Cases</h2>
<ul>
<li>User can see a display showing the current number entered or the result of the last operation.</li>
<li>User can see an entry pad containing buttons for the digits 0-9, operations - '+', '-', '/', and '=', a 'C' button (for clear), and an 'AC' button (for clear all).</li>
<li>User can enter numbers as sequences up to 8 digits long by clicking on digits in the entry pad. Entry of any digits more than 8 will be ignored.</li>
<li>User can click on an operation button to display the result of that operation on:
<ul>
  <li>the result of the preceding operation and the last number entered OR</li>
  <li>the last two numbers entered OR</li>
  <li>the last number entered</li></li>
</ul>
<li>User can click the 'C' button to clear the last number or the last operation. If the users last entry was an operation the display will be updated to the value that preceded it.</li>
<li>User can click the 'AC' button to clear all internal work areas and to set the display to 0.</li>
<li>User can see 'ERR' displayed if any operation would exceed the 8 digit maximum.</li>
</ul>
<h2>Constraints</h2>
<li>You may not use the eval() function to execute calculations.</li>

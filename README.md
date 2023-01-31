# assignment2-sattor
# sri harshika sattor
###### cricket
 Being a scholler in the ffree schoole of Guldeford hee and diverse of his fellows did runne and play there at creckett and other plaies.

**This is sri harshika sattor**
**I am from Hyderabad**
---
# favourite team is Indian cricket team
Three best players are
   1. Dhoni
   2. Virat kohli
   3. Hardik pandya

   * Pakisthan cricket team
   * Newzeeland cricket team
   let's go to the link
   [please](https://github.com/sriharshika/assignment2-sattor/blob/main/AboutMe.md)

# Table creation
In this table we are showimg the list of countries to visit 
| Country    | Reason for Visit| No of Days  |
|---------   | ----------------| ----------  |
| India      | Tradition        | 6 months   |
| US         | Climate          | 3 months   |
| UK         | Tourism          | 1month     |
|Switzerland | Location         | 1month     |

# Pithy Quotes
>'It is never too late to be what you might have been.' – ***George Eliot ***
>'Pain is inevitable. Suffering is optional.' – ***Haruki Murakami***

>How can I make a sticky table header? [please](https://stackoverflow.com/questions/71782720/how-can-i-make-a-sticky-table-header)

```
function UpdateTableHeaders() {
   $("div.divTableWithFloatingHeader").each(function() {
       offset = $(this).offset();
       scrollTop = $(window).scrollTop();
       if ((scrollTop > offset.top) && (scrollTop < offset.top + $(this).height())) {
           $(".tableFloatingHeader", this).css("visibility", "visible");
           $(".tableFloatingHeader", this).css("top", Math.min(scrollTop - offset.top, $(this).height() - $(".tableFloatingHeader", this).height()) + "px");
       }
       else {
           $(".tableFloatingHeader", this).css("visibility", "hidden");
           $(".tableFloatingHeader", this).css("top", "0px");
       }
   })
};

```
snippet source code [link](https://css-tricks.com/snippets/jquery/persistant-headers-on-tables/)



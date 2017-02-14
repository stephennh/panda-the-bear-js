1. $('.profile-image')

1. $('#left-image')

2. $('.highlight').text('Stephen')

3. $('#employment > .info-title').html("<i class=\"icon-suitcase\"></i> &nbsp; Volunteer")

4. $('.bar-default')[2].remove()

5. $('body').css('background-color','cyan')

6. $('.highlight').css('color','blue')

7. $('h1').css('font-family','monospace')

8. $('.action-icon-bg').css('background-color','cyan')

9. $('form > #name').attr('placeholder','Identify Yourself')

10. $('form > #message').attr('placeholder','State Your Business')

11. $('form > #name').attr('value','Your Nemesis')

12. $('form > #email').attr('value','koalathebear@gmail.com')

13. $('form > #submit').attr('value','En garde!')

  1. $('#submit').attr('disabled','true')

  2. $('.bio-info').empty()


Adding Elements to the DOM

1. $('#right-image').clone().appendTo('form')

2. for (var i=0; i<10; i++) { $('#right-image img').clone().insertAfter('form') }

3. var listItem = document.createElement('li');
   var leftSpan = document.createElement('span');
   var lastUpdated = document.createTextNode('Page last updated on');
   var rightSpan = document.createElement('span');
   var currentDate = document.createTextNode(Date());
   leftSpan.appendChild(lastUpdated);
   rightSpan.appendChild(currentDate);
   listItem.appendChild(leftSpan);
   listItem.appendChild(rightSpan);

   $('.bio-info').append(listItem)

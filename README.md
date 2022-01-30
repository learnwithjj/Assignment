# Assignment

1)The table with id="age-table".
  table=document.getElementById("age-table")
2) All label elements inside that table (there should be 3 of them).
  var age=document.getElementById("age-list")
  label=age.getElementsByTagName("label")
3) The first td in that table (with the word “Age”).
    age=document.getElementsByTagName("td")[0]
4) The form with name="search"
    search=document.querySelector("form")
5) The first input in that form
    var form=document.getElementsByTagName("form")[1]
    firstinput=form.querySelector("input")
6) The last input in that form.
    var form=document.getElementsByTagName("form")[1]
    input=form.getElementsByTagName("input")
    lastinput=input[input.length-1]

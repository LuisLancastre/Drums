Hey

The issue here is that I was able to make the drums produce sound when I used the keyboard, but when I click on them with the mouse nothing happens, still trying to figure it out.



///////////// UPDATE /////////////



The error was this variable " var buttonInnerHtml = this.innerHtml; " And because the Html was lowercased happened to make the mouse click to not function the way it was supposed to.

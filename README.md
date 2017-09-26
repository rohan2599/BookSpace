# BookSpace
Virtual simulation of the 'IIITV Library'.

To maamla ye he(Abstract Explanation):

Apna program run karte hi vo sabse pehle uska IIITV ID mangega.
Fir usko ek window dikaenge, jisme tabs honge with names as types of books, jese Mathematics, Machine learning, Literature.
Kisi ek tab pe click karega to us genre k jitne available books h, or unki kitni quantity h, book k respective covers k sath show karni rahegi use.
Fir kisi ek book par agar vo click kartae, to 2 options will be shown, Read or Issue. Vo agar read kartae to us book ka pdf file open karke usko denae. Or agar issue kartae, to quantity check karke, agar available hui to sidha use message show karne k 'Issued! Collect within 45 min from the library', uski due date ke sath or fine per day late.
Agar 45 min me vo agar library se issue nai kartae to, the issue will be cancelled.
Iske baad use previous menu me le janae and now he can only read and not issue.
Or isi menu me hi side me ek 'exit library' option hoga. Agar vo click kartae to program terminates with msg "Thanks for the visit".

Implementation:

Start breaking everything into objects. Jese, there's a book named 'CLRS'.
Therefore uska:
      Object name: CLRS
      Type(Class): Algorithms
      Methods: read(), issue()
      Attributes: price, author, publication, edition.
Isi tarah start objectifying things, which will lead you to making respective classes for their implementation, and consequent methods. The tester.java contains the main() method jisme tumhe apni classes k objects banake unhe test karna rahega, matlab vo thik se work karrae h k nai. Give sensible names to classes, methods and variables. Take care of proper indentation, i.e.

int book(String s){
  for(...){
    int h;
  }
}

and not this:

int book(String s){
for(...){
int h;
}
}

For contributing:
First clone, then make a branch, make changes to branch, push the changes, then make a pull request.




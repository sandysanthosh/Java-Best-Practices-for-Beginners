Welcome to the Java-Best-Practices-for-Beginners wiki!



->prefer empty collections instead a null:

String bad = new String("bad program");
String good = "good programmig";
s.o.p("a");
s.o.p('a');


->avoid memory leaks:


->memory leask often cause performance degredation of software

available release databace connections when querying is complete
try to use final block often possible
release instance stored in static tables

->null pointer exception:

if(files==null){
throw new NullPointerException("file list cannotbe null");
}


->JSON: -> java script object notation

main(){
JSONObject obj = new JSONObject ();
obj.put("novel","godan");
obj.put("author","munschi");
JSONArray array = new JSONArray();
array.add("language":"tamil");
array.add("year":"2190");
obj.put("novel detail", novelDetails);
}

->simple string search:

String mystring = " i am string";
if(mystring .indexof("string")==1){
s.o.p("string not found");
}

->listing content of directory:

file file = new file("//home//user//document");
String files[]= file.list();
for(int i=0;i<files.length();i++{
s.o.p(files[i]);
}
}

->PDF Export:
->expor a table to pdf
->avoid using float use big deciamal instead
->use equals over ==

->document ideas steps:

strategize
prepare
document
review
implementation

prepare design document
mention assumptions properly
get the document peer review
take sign off on them

->design pattern:

developers to incorporate best software design principle
common platform for developers across the globe
collaborate and easier to communicate

->rule:
 10-50-500 rule:

10 : no package can have more than 10 classes
50 : no method can have more than 50 lines of code
500: no class can have more than 500 lines of code

->collections:

java is shipped with a few collections - vector,stack,hashtable...

use of collections make the code reusable and interoperable..
collections makes code more strucked,easier to understand and maintainable..
out of box collections also well tested so that quality of code is good..

Validating BigDecimal data type for nulls In Java

-> rescale imag:
    BufferedImage imgsource

->measuring time:
->require measuring time measurment

long startTime = system.currentTimeMillis();
long endTime = system.currentTimeMillis() - startTime();

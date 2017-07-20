
function Programmer(name, title, age, language){
  this.name="name",
  this.title="title",
  this.age="age",
  this.language="language",
  this.PrintStats= function(){
    console.log("Name:" + this.name +"Title:" +this.title + "Age:" + this.age + "Language: "+ this.language);
  };
}
var hoe = new Programmer ("Hoe", "Queen", "350", "Omnilingual");
hoe.PrintStats()

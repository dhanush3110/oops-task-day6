//Day-6 oops task
//1.)class-movie
// class film{
//     constructor(title,studio,rating){
//        this.title=title;
//        this.studio=studio;
//        this.rating=rating;
//     }
//     displaytitle(){
//       console.log(this.title)
//     }
//     displaystudio(){
//         console.log(this.studio)
//     }
//     displayrating(){
//         console.log(this.rating)
//     }

// }

// let obj=new film("singam","greenstudio",3.5)
// obj.displaytitle()
// obj.displaystudio()
// obj.displayrating()


//3.)write a "person class to hold all the details"


// class person{
    
//     static personal(){
//  let details={name:'dhanush',
//               age:25,
//               education:'msc',
//               college:'Anna university',
//               height:5.8,
//               weight:76,
//               hobby:'music'}
//        console.log(details)
//     }
 
// }
// person.personal()

//4.)write a class to calculate the uber price

// class uber_price{
//     constructor(delivery1){
//         this.delivery1=delivery1;
        
//     }
//       pickfood(){
// var   food   = {chickenrice:120,
//              chickencurry:150,
//              biriyani:120,
//              muttoncurry:200,
//              paratho:25,
//              pizza:200,
//              dhosa:50,
//              idly:50,
//              waterbottele:20}       
//              return food;  
//     }

//     distancetravel(){
//        let distance={near:25,
//                     midrange:35,
//                     long:50,
//                     other:100
//                  }
//                  return distance;
//     }
//     calculation(){
        
           
//             console.log("total cost of uber price is "+this.delivery1+" rupees")
//     }
     
// }

// //create object for call
// var obj=new uber_price()
// //pickfood
// var food_reference=obj.pickfood()
// var keys=Object.keys(food_reference)
// var values=Object.values(food_reference)
// food_length=keys.length;

// let input1="chickenrice";

// for (let i=0;i<food_length;i++){
//  if(keys[i]==input1){
//  input1_price=values[i]
//  };
// };

// //distancetravel
// var distance_reference=obj.distancetravel()
// var keys1=Object.keys(distance_reference)
// var values1=Object.values(distance_reference)
// distance_length=keys1.length;

// let input2="near";

// for (let i=0;i<distance_length;i++){
//     if(keys1[i]==input2){
//      input2_price=values1[i]
//     };
// };
// //adding total cost
// let total_cost=input1_price+input2_price;
// //recreate same for considering variable
// var obj=new uber_price(total_cost)
// obj.calculation()


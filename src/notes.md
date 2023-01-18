//types
let name: string;

//any type
// let name: any;

//Unknown type is recommended over any type
//let name: unknown;

//this is a union, age can be a number or a string 
let age: number | string;
let isStudent: boolean;
let hobbies: string[];
//tuple contains fix amount of value
let role:[number, string];
//role = [5, "edad"];

//FUNCTIONs
// function printName(name: string) {
//   console.log(name)
// }

//declaring what the function will take in
//function will take in name as a string and void means its not returning anything
// let printName: (name: string) => void;
// printName("mason")


//TYPE
// type Person = {
//   name: string;
//   age?: number;
//   //question mark means its optional
// }

//INTERFACE
interface Person {
  name:string;
  age?:number;
}

let person: Person = {
  name: "mason",
}

//Array of objects
let lotsOfPeople: Person[]; 
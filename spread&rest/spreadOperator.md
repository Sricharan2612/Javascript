Spread Operator --->
The JavaScript spread operator (...) allows us to quickly copy all or part of an existing array or object into another array or object.

spread operator can be used with both the arrays as well as objects.

eg.1
const numbersOne = [1, 2, 3];
const numbersTwo = [4, 5, 6];
const numbersCombined = [...numbersOne, ...numbersTwo];

eg.2
const myVehicle = {
  brand: 'Ford',
  model: 'Mustang',
  color: 'red'
}

const updateMyVehicle = {
  type: 'car',
  year: 2021, 
  color: 'yellow'
}

const myUpdatedVehicle = {...myVehicle, ...updateMyVehicle}
# encryptions
Key logger domain format problematic web development
const inputs = document.querySelectorAll(".controls input");

//console.log(inputs);

//inputs.forEach((i) => console.log(i)); // this returns all the values in inputs

// We can make our own attributes with data- in the beginning of it

// This function will return the current value

function handleUpdate() {

	// console.log(this.value);	const suffix = this.dataset.sizing || "";

	//console.log(this.name);

	document.documentElement.style.setProperty(

		`--${this.name}`,

		this.value + suffix

	);

}

// Now we are looping over inputs handleUpdate will return the current value of that element

controls input");

//console.log(inputs);

//inputs.forEach((i) => console.log(i)); // this returns all the values in inputs

// We can make our own attributes with data- in the beginning of it

// This function will return the current value

function handleUpdate() {

	// console.log(this.value);

	const suffix = this.dataset.sizing || "";

	//console.log(this.name);

	document.documentElement.style.setProperty(

		`--${this.name}`,

		this.value + suffix

	);

}

// Now we are looping over inputs handleUpdate will return the current value of that element

inputs.forEach((input) => input.addEventListener("change", handleUpdate));

inputs.forEach((input) => input.addEventListener("mousemove", handleUpdate));

// const inputs1 = Array.from(inputs);

// console.log(inputs1);

<script>
	import Card from "$lib/Card.svelte";
</script>

<h1> Basics </h1>

<Card title='String'>
	A `String` is a mix of letters and numbers, wrapped in single or double quotes and characters can be repeated.
	Ex. 
		<li>"MicDocs7898"</li>

	<br />
	Strings and numbers can be added <strong>together with a +</strong> operator
	Ex.
	 	<li> "I am " + (55 / 5) + " a string." = {"I am " + (55 / 5) + " a string."}</li>
</Card>


<Card title='Number'>
A <strong>number</strong> can be represented as int. The value can range from any number. We can use int to define variables holding numbers.
Ex.
<li> </li>
</Card>


<Card title='Variable'>
A <strong>variable</strong> can be any number or letter. Ex.
<li>let a = 10 let b = 5. Now if we were to do a + b and execute, we would come by 15.</li>
Knowing this will let us create more complex ideas.
</Card>

<Card title='Boolean'>
A <strong>boolean</strong> is a data type with two attainable values, True or false.
Ex. <li>function image, showimage = true (of course in proper formatting, but this will give you an idea)</li>
This is key to creating websites.
</Card>

<Card title='Function'>
<strong>Functions</strong> are also used with booleans as shown above, they are a set of instructions compounded together to create different outcomes.
Ex. <li>function 'insert variable'() window.close(); </li>
In the insert variable you can create a buttona which when clicked will close the window.
</Card>


<style>
	:global(body) {
		background: rgb(255, 255, 255);
	}
	h1 {
		text-align: center;
		padding-top: 1px;
	}
</style>
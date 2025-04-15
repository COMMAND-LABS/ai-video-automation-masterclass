# Part 2

In Make.com, each module, or node, or step in our automation, or scenario as it’s so called in Make.com, allows us to customize how it behaves.

And sometimes the module has some “advanced” ways that we can configure it

- So now we are going to enable the “Advanced Settings“ on the OpenAI module
    - Switch the “Response Format” to be `JSON Object`
    - Switch the “Parse JSON Response” to be `Yes`
- Add “json” to the prompt and rerun
- Now let’s try this…
- While there are other ways of outlining your desired JSON output, I like this way of outlining the general structure of a json object best
- https://www.google.com/search?q=javascript+primitive+types
- In Javascript, the programming language that JSON originally comes from, there are 7 basic types of values
	- String
	- Number
        - BigInt
        - Boolean
        - Symbol
	- Null
        - Undefined
- Using JSON output mode is nice because it allows us to easily reference our A.I. generated data later on in our automation as we will soon see

If you are new to this and you find this confusing don’t worry as you will pick up JSON very fast. There is really not much more to it than that.

JSON is just a way of storing information. You store your information in key-value pairs in order to represent something and that thing can by anything.

I promise that is about as technical as we will be getting in this video

```txt
Create 2 scenes for a movie

json output

{
  "title": string;
  "scenes": {
    "title" string;
    "shortDescription": string;
  }[];
}
```

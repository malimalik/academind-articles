<!-- In this article, he is assuming that the person reading it is already familiar with `useState()`
What perspective is he coming from?

His perspective is to keep it as concise as possible while not giving out too many details.
This is not a blog, he wants to be as concise as possible.

What he could do better?

- He doesn't have an introduction
- He doesn't have a conclusion
- He doesn't have visuals
- He needs to make use of AI visuals
-->

# Avoid `useState()`

<!-- There should be an image with regards to `useState`.  The content can be much higher value and much better. -->

The `useState` hook is the most ubiquitous hook in React, enabling developers to handle a components local state with ease. While handling state locally works in certain scenarios, there are scenarios that are more suitable for other alternatives.

In this article, we will explore alternative strategies for both user experience and app performance without compromising core principles of React.

<!--

- The title shouldn't be called, "avoid useState()", it should be called Common pitfalls of useState(),
though I get why he is saying to avoid `useState()`. It's basically because he wants the user to click.
 -->

## Understanding `useState()`

For those who are kind of familiar with `useState`, there should be a visual that lets them recap `useState`. The article should be more detailed than the video itself, unless the article is supposed to be a TL;DR.

### What `useState()` does

<!-- This section should include the use cases of useState and where it shines. This is so we set up the stage to provide the motivation for
 -->

## When to rethink `useState()`

<!-- This should be called:

- "Situations when useState is not ideal"
- The limited applicability of useState
- Better alternatives to `useState`
- When not to use `useState()`
-
-  -->

<!-- Now that we have seen places where the useState() hook may noe be as applicable, let's take a look at when we should rethink useState() -->

### Form Data Handling

```jsx

```

```jsx

```

```jsx

```

```jsx

```

```jsx

```

### Utilizing browser features for form submission

<!-- 
- Explain the problem the browser features are looking to solve
- Why they are efficient at solving this problem
- Where `useState` fails

The useState example should show where useState fails so it creates a compelling example for why it shouldn't be used.
The example should show the pitfall of `useState` under in this scenario
This way, they are aware.

Each section should be written in the following way:
- Here is why you shouldn't make use of `useState`
- Here is why useState isn't ideal for this scenario
- Here is why you need alternative solutions.


 -->

### Storing state in the URL




### Persisting state with Local Storage

## Conclusion

<!-- The conclusion should underscore the following:

* Why making use of `useState` is good but there are limitations
* Why and when other alternatives are needed
* How these other alternatives do not undermine or minimize the usefulness of `useState()`

 -->

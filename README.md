# To-do App with Svelte and Firebase

$\textcolor{ForestGreen}{\textbf{\emph{Completed:}}} \text{\emph{ Sunday, Oct 30, 2022.}}$

## Demo
Run the following commands to start the app at `http://localhost:8080/`.

```bash
npm install
npm run dev
```

Have fun!

## Code Source 
The code for this project is adapted from binita-g's [todo-app-svelte](https://github.com/binita-g/todo-app-svelte/tree/2af20f0c43083bd0953c260dcb0efe1b9ae6ce38) Github Project, with a few additions as noted in the [Improvements section](#improvements) below.

## Features  
- We provide login and handle database storage through Google's Firebase.
- To add tasks, input the task name and select "Add Task."
- When you have some tasks to work over, you can click on the checkmark on the left of each item to mark them as completed. Click the "X" mark to undo.
- Click the trash icon to delete the task.

## Improvements  
1. I spent *way too much* time in forums trying to figure out the refresh bug. Here are some of the sources I looked at, but nothing worked unfortunately: [1](https://developer.mozilla.org/en-US/docs/Learn/Tools_and_testing/Client-side_JavaScript_frameworks/Svelte_variables_props), [2](https://elad-rosenheim.medium.com/hot-content-reload-with-sveltekit-contentful-35f12c8ccbbc), [3](https://framework7.io/svelte/page), [4](https://github.com/mefechoel/svelte-navigator/issues/42), [5](https://svelte.dev/repl/638d0a980c1b47fc8b1e7c270c8e5bc2?version=3.38.3), [6](https://svelte.dev/repl/37131b08ed674fa193cfdb877f9d428d?version=3.52.0), [7](https://docs.cypress.io/guides/core-concepts/retry-ability#What-you-ll-learn), [8](https://svelte.dev/repl/286559382580492c8288e53a3597d7e1?version=3.28.0), [9](https://developer.mozilla.org/en-US/docs/Learn/Tools_and_testing/Client-side_JavaScript_frameworks/Svelte_reactivity_lifecycle_accessibility), [10](https://svelte.dev/docs#template-syntax-key), [11](https://flaviocopes.com/svelte-rerender-on-demand/), [12](https://stackoverflow.com/questions/58403515/how-to-force-rendering-in-svelte-3), [13](https://stackoverflow.com/questions/56891190/how-to-trigger-force-update-a-svelte-component).
1. Changed some of the app language to make it user-friendly.
1. Added comments to demonstrate code understanding.

## Reflection 
> _What are the significant software concepts that this combination of technologies has that each previous set of technologies did not? Or that they handle significantly differently?_

It reminded me of Flutter and seemed like a nice bridge between HTML and JS, offering additional functionality. I would say the ease of use is between HTML/JS and Flutter.

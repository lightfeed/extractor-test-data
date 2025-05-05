Lorem ipsum dolor sit amet, consectetur
=======================================

Lorem ip Lorem ipsum dolo

Lorem ipsu Lorem Lorem ipsum

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercit

Lorem ipsum dolor si
--------------------

The `async` keyword is used to declare an asynchronous function. An async function automatically returns a promise, and the value returned by the function will be resolved with the returned promise.

The `await` keyword can only be used inside an async function. It pauses the execution of the function until the promise is resolved or rejected.

Lorem ipsum d
-------------

    
    async function fetchData() {
      const response = await fetch('https://api.example.com/data');
      const data = await response.json();
      return data;
    }
        

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo cons

Lorem ipsum do
--------------

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut

    
    async function fetchData() {
      try {
        const response = await fetch('https://api.example.com/data');
        const data = await response.json();
        return data;
      } catch (error) {
        console.error('Error fetching data:', error);
        throw error;
      }
    }
        

Lorem ipsu
----------

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi

Lorem ipsum dolor sit
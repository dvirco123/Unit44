### Conceptual Exercise

Answer the following questions below:

- What is the purpose of the React Router?
React Router is a JavaScript framework that lets us handle client and server-side routing in React applications. It enables the creation of single-page web or mobile apps that allow navigating without refreshing the page. It also allows us to use browser history features while preserving the right application view.

- What is a single page application?
A single-page application (SPA) is a Web app that is presented to the user through a single HTML page to be more responsive and to more closely replicate a desktop application or a native app.

- What are some differences between client side and server side routing?
with server-side routing you download an entire new webpage whenever you click on a link, with client-side routing the webapp downloads, processes and displays new data for you.

- What are two ways of handling redirects with React Router? When would you use each?
navigate('/about', { replace: true

- What are two different ways to handle page-not-found user experiences using React Router? 
404 page not found in the react application with React Router, use a wildcard path with an asterisk('*') and add it to the very last path of our routes with <PageNotFound/> as the element. Or we can redirect to sitename.com/404 path using the Navigate component imported from the react-router-dom.

- How do you grab URL parameters from within a component using React Router?
Using React Router, when you want to create a Route that uses a URL parameter, you do so by including a : in front of the value you pass to Route 's path prop. Finally, to access the value of the URL parameter from inside of the component that is rendered by React Router, you can use React Router's useParams Hook.

- What is context in React? When would you use it?
What is context in React? React's context allows you to share information to any component, by storing it in a central place and allowing access to any component that requests it (usually you are only able to pass data from parent to child via props).

- Describe some differences between class-based components and function
  components in React.
The most obvious one difference is the syntax. A functional component is just a plain JavaScript function which accepts props as an argument and returns a React element. A class component requires you to extend from React. Component and create a render function which returns a React element.


- What are some of the problems that hooks were designed to solve?
As stated earlier, hooks were created to solve three problems: wrapper hell, huge components, and confusing classes. Let's take a look at each of these in more detail.

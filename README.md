Fiverr App 
    React 18, Vite, Sass, ESLint

    ESLink - To catch errors quickly

    To install ESLint
        - npm add eslint --dev
        - npx eslint --init

    - Creating all the pages
     - home
     - gigs
     - gig
     - login
     - add
     - message
     - messages
     - myGigs
     - orders
     - register
    
    Note - All pages and Components should create inside the src folder

    - Creating Components
     - Navbar
      - Sticky navbar 
       - changed color and sticky while scroll
        - used useState and useEffect
         - useState used for changing the state
         - useEffect used for changing the state based on the scroll
     - React Router Dom
      - used createBrowserRouter, RouterProvider
       - create router variable and created route using createBrowserRouter method and assign it to RouterProvider
       - Here header and footer will not change, so we will using the Outlet method from react-router-dom
        - Create Layout function and assign outlet architecture and assign to root path in the createBrowserRouter method. Other routes will be there under children
      - useLocation method is used to navigate the pages based on the url  
    


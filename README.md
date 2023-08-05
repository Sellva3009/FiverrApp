Github
    Github is the hub for storing the code and spread through big teams

    Initialize the git by running "git init" command
    git status - check for the latest changes
    git add <filename> - To add the changed file name to the branch
    git add * or git add . - to add all files changed
    git commit -m "message" - to snapshot all files to the branch
    git log - To check for the latest commit id and other info


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

    - Featured components  
    


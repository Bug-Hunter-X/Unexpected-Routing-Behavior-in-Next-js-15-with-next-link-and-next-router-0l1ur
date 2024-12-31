# Next.js 15 Routing Bug

This repository demonstrates a potential unexpected behavior related to client-side routing in Next.js 15 when using both `next/link` and `next/router` for navigation.

## Bug Description
The bug occurs when navigating between pages using `next/link` for the initial navigation and then using `next/router.push` for subsequent navigation. In some cases, the routing might not work as expected, leading to unexpected page behavior or rendering issues.

## Steps to Reproduce
1. Clone this repository.
2. Run `npm install` to install dependencies.
3. Run `npm run dev` to start the development server.
4. Navigate to the `/about` page using the link provided on the homepage.
5. Click the "Go back Home" button. Observe the behavior. The navigation might not be smooth or expected. 

## Solution
The provided solution demonstrates a potential fix or workaround for this behavior by applying specific techniques to handle routing consistently between pages.

## Technologies Used
* Next.js 15
* React

## Contributing
Contributions are welcome! If you find another way to solve this issue or discover another unexpected behavior, please open a pull request or issue.
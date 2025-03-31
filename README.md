![Dog and Pony Studios](https://www.dogandponystudios.com/app/themes/dps/assets/public/images/logo-fbe89868bd.svg)

# Frontend Developer Test

**Welcome to our Frontend Developer Test**

This test consists of a series of tasks which may take a few hours to complete, depending on your experience level. The primary purpose of this test is to infer your __logical thinking__, __problem-solving skills__, and __fidelity to the design and prototype__.

## Project Setup Instructions

1. Create a __private__ repository.
1. Setup Next.js. Run `yarn create next-app` and follow these instrucions:
    * __What is your project named?__ dps-frontend-test-_yourgithubusername_
    * __Would you like to use TypeScript?__ Feel free to pick the option you'd like
    * __Would you like to use ESLint?__ … Yes
    * __Would you like to use Tailwind CSS?__ … Yes
    * __Would you like your code inside a 'src/'__ … Yes
    * __Would you like to use App Router? (recommended)__ … Yes
    * __Would you like to use Turbopack for 'next dev'?__ … Yes
    * __Would you like to customize the import alias ('@/*' by default)?__ … No
1. To run the project locally, use `yarn dev`

## Scenario

To recreate the design and funcionality of [the design](https://www.figma.com/design/HLTG9j1j1L4UrLdZDuPRkW/Front-end-Test-Workflow-Page?node-id=10850-397&p=f&t=7uqZS4yRSuramerm-0) presented.

## Tasks

Using the Nex.js project you set up following the instructions above, create [the design](https://www.figma.com/design/HLTG9j1j1L4UrLdZDuPRkW/Front-end-Test-Workflow-Page?node-id=10850-397&p=f&t=7uqZS4yRSuramerm-0) using [Next.js](https://nextjs.org/) and [TailwindCSS](https://tailwindcss.com/).

__src/app/page.js__  
This will be the homepage you are creating.  
Please fetch the data for the page from `http://dps-dev-test.n.dps.sh/data.json` and __set the revalidate value to 60__.  
The JSON response will contain the content and images needed for the page you are creating.

__src/app/layout.js__  
Adjust this file as needed to remove what you don't need and import the correct font-family for this project.

## Tips

1. Carefully review the Figma file, which includes both desktop and mobile designs. On the right side of the designs, you will find handoff annotations detailing hover states, the select dropdown, the carousel, typography, and overlays.
1. Please use Tailwind for the styling. While handwritten CSS and Tailwind JIT can be used, they should be avoided unless absolutely necessary. Feel free to create a tailwind.config.js file and adjust anything you need.
1. All images provided in the JSON data use [Imgix](https://www.imgix.com/). This means image manipulation can and should be used to ensure you are using the proper [image sizes](https://docs.imgix.com/en-US/apis/rendering/size), so you're not loading images that are larger and heavier than necessary ([keep device pixel ratio in mind](https://docs.imgix.com/en-US/apis/rendering/device-pixel-ratio)).
For example, these URLs will give you different size images from the same source image:  
    * Original/source: https://dps-dev-test.imgix.net/image-hero.png
    * Resized: https://dps-dev-test.imgix.net/image-hero.png?w=200
    * Resized and cropped: https://dps-dev-test.imgix.net/image-hero.png?w=200&h=200&fit=crop
1. Maintain a well-organized codebase to ensure clarity and ease of maintenance.
1. Create reusable components wherever possible to minimize code duplication.
1. Prioritize semantic HTML and accessibility. Ensure that the entire page and its elements are fully navigable via keyboard (e.g., using the Tab key and arrow keys where applicable).
1. The carousel must be fully functional. Refer to the handoff annotations in the Figma file for specific requirements.
1. You are not expected to build everything from scratch. Feel free to leverage third-party libraries for features such as the carousel and select fields.
1. The newsletter form does not need to be functional but should adhere to a semantic and accessible structure.
1. Specific guidelines for CSS transitions have not been provided. Please incorporate transitions where appropriate, such as on link and button hover states, and adjust the duration and timing to achieve a polished and cohesive user experience.
1. Elements and sections should feature smooth transitions as they enter the viewport. While the exact implementation is left to your discretion, this is an opportunity to showcase your design sensibilities by delivering animations and transitions that enhance the overall look and feel of the application.
1. The developed page should aim for a high degree of precision, closely matching the provided design to ensure a pixel-perfect implementation.
1. Be mindful of the page's loading performance.
1. Please ensure your readme file contains valid and simple instructions if any special setup is needed.
1. Ensure your project works both in dev and after build (`yarn build`).
1. Verify the full functionality of your page prior to submission.

## Deadline

You´ll have up to 7 consecutive days to work on the test.

## Submissions

Please submit your test as a __private__ Github repository URL, along with a readme file containing any relevant information about your project.

Your GitHub repository should have the following naming format:  
dps-frontend-test-_yourgithubusername_

Please add [Fez](https://github.com/felipesnts) with view access to your __private repository__.

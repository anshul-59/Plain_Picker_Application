
# Place Picker
This is a Place Picker web app, created to understand state management. It is created using React and Vite is used to provide zero configuration setup to focus more on writing code and implimenting logic.

Vite:

Enables Hot Module Replacement (HMR), as seen in the animation below
Makes it easy to deploy your website to the internet
Helps you import and manage (potentially sensitive) environment variables
Makes it easy to bolt-on technologies you need, for example, TypeScript

## Getting Started




### Available Scripts

In the project directory, you can run:

### `npm run dev`



The page will reload when you make changes.\
You may also see any lint errors in the console.
## Features

A local Database is used to fetch the places. Each place has a set of coordinates to identify its location and distance between two places is calculates using Haversine formula.

This code provides a feature to sort an array of places by their distances from a given reference point (latitude and longitude). It's useful in applications that involve location-based services, such as finding nearby restaurants, attractions, or services. (Logic can be found in loc.js)

The places are arranged from closest to the farthest using the current location of the user.

A modal component is created which creates a modal dialog that can be opened or closed based on the value of the open prop. It uses the <dialog> element, along with the showModal and close methods, to manage the modal's visibility. The createPortal function ensures that the modal is rendered outside the normal DOM hierarchy, typically at the end of the document body, to avoid styling conflicts and improve accessibility.


## Features

A local Database is used to fetch the places. Each place has a set of coordinates to identify its location and distance between two places is calculates using Haversine formula.

This code provides a feature to sort an array of places by their distances from a given reference point (latitude and longitude). It's useful in applications that involve location-based services, such as finding nearby restaurants, attractions, or services. (Logic can be found in loc.js)

The places are arranged from closest to the farthest using the current location of the user.

A modal component is created which creates a modal dialog that can be opened or closed based on the value of the open prop. It uses the <dialog> element, along with the showModal and close methods, to manage the modal's visibility. The createPortal function ensures that the modal is rendered outside the normal DOM hierarchy, typically at the end of the document body, to avoid styling conflicts and improve accessibility.


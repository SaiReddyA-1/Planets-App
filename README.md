Here is the revised version with a static link for the video:

I've built this **Planets App** by applying the concepts we have learned till now.

### Refer to the video below:

![Planets App Output](https://assets.ccbp.in/frontend/content/react-js/planets-app-output.mp4)

### Design Files

- [Medium (Size >= 768px), Large (Size >= 992px) and Extra Large (Size >= 1200px)](https://assets.ccbp.in/frontend/content/react-js/planets-app-lg-output.png)

### Set Up Instructions

- Download dependencies by running `npm install`
- Start up the app using `npm start`

### Completion Instructions

The app includes the following functionalities:

- `planetsList` is displayed using **React Slick**
- The `PlanetsSlider` component receives the `planetsList` as a prop. It consists of a list of planet objects with the following properties:

  | Key         | Data Type |
  |-------------|-----------|
  | id          | String    |
  | name        | String    |
  | imageUrl    | String    |
  | description | String    |

- When the next button is clicked, the next planet details in the `planetsList` are displayed
- When the previous button is clicked, the previous planet details in the `planetsList` are displayed

![Planets Keys Breakdown](https://assets.ccbp.in/frontend/content/react-js/planets-app-keys-breakdown.png)

### Components Structure

![Component Structure Breakdown](https://assets.ccbp.in/frontend/content/react-js/planets-app-component-structure-breakdown.png)

### Implementation Files

Use these files to complete the implementation:

- `src/components/PlanetsSlider/index.js`
- `src/components/PlanetsSlider/index.css`
- `src/components/PlanetItem/index.js`
- `src/components/PlanetItem/index.css`

### Important Note

- To build this project, I referred to the [React Slick](https://learning.ccbp.in/frontend-development/course?c_id=2f4192f7-7495-49ca-a6ce-6b74005e25f1&s_id=c1dc8b6e-864b-4417-9767-471b9e745405&t_id=416f0cab-8425-413b-9157-c7b4d4ae4467) reading material.

**The following instructions are required for the tests to pass:**

- The planets should have the `alt` attribute set to the value of the `name` key from the planet objects in the `planetsList`
- The app should contain an HTML container element with `data-testid` as `planets`

### Resources

Image URLs:
- [Planets Background Image](https://assets.ccbp.in/frontend/react-js/planets-app/planets-bg-img.png)

Colors:
- Hex: #f8fafc
- Hex: #f1f5f9
- Hex: #05acff

Font-families:
- Roboto

> ### _Things to Keep in Mind_
>
> - All components you implement should go in the `src/components` directory.
> - Don't change the component folder names as those are the files being imported.
> - **Do not remove the pre-filled code**.

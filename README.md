# README

This application is built using several first CLI commands from the [Starting Development](https://redwoodjs.com/docs/tutorial/chapter1/installation) tutorial document:

```
yarn create redwood-app --ts ./minimal-application
cd minimal-application

yarn rw dev
yarn redwood generate page home /
yarn redwood generate page about
```

followed by editing the two newly created pages to be

```
import { MetaTags } from '@redwoodjs/web'

const HomePage = () => {
  return (
    <>
      <MetaTags title="Home" description="Home page" />

      <h1>Home Page</h1>
    </>
  )
}

export default HomePage
```

and

```
import { MetaTags } from '@redwoodjs/web'

const HomePage = () => {
  return (
    <>
      <MetaTags title="Home" description="Home page" />

      <h1>Home Page</h1>
    </>
  )
}

export default HomePage

```

Note that we removed nearly everything from these two pages as all the content and navigation will be created by all supported UI libraries:

- [Chakra UI](https://github.com/adriatic/rw-chakra) <br>
- [Daisy UI](https://github.com/adriatic/rw-daisyUI) <br>
- [Tailwind UI](https://github.com/adriatic/rw-Tailwind-UI) <br>
- [Bootstrap 5](https://github.com/adriatic/rw-Boostrap-5) <br>

Each of these repositories contains the code from [rw-minimal-app](https://github.com/adriatic/rw-minimal-app) which is subsequently augmented by the code from the respected UI components library.


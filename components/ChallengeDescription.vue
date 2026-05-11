<template>
  <div>
    <h1>Frontend Coding Challenge</h1>

    <p>
      This project is a basic
      <a
        href="https://nuxt.com/docs/getting-started/introduction"
        target="_blank"
      >
        Nuxt 3
      </a>
      project which uses some free API data to fetch a list of users and display
      their information in a list.
    </p>

    <p>
      By clicking on one of the list's element, we are redirected to the user's
      profile, which misses the call to the user information at the moment.
    </p>

    <p>
      The website is voluntarily not well-designed and you don't have to work on
      this part.
    </p>

    <h2 class="challenge-subtitle">Tasks</h2>

    <ol>
      <li>
        Change the current layout to bring some responsive behaviour. Only
        implement a single solution, but try to think of different solutions
        that could be used to achieve responsiveness.
      </li>

      <li>
        Implement the call to the user's information when redirected to their
        profile - you will use the endpoint
        <code>https://jsonplaceholder.typicode.com/users/{id}</code>
        and a
        <a
          href="https://nuxt.com/docs/getting-started/data-fetching"
          target="_blank"
        >
          Nuxt built-in hook
        </a>.
      </li>

      <li>
        Display a few information, but do not add any styling. Change the Nuxt
        configuration to behave in SPA (single-page-application) mode, and
        compare the behavior when previously using the SSR
        (server-side-rendering - default mode) mode.
      </li>
    </ol>

    <p>
      The code will then need to be present in a public repository and you will
      provide us the GitHub link when you are done with it.
    </p>

    <h2 class="challenge-subtitle">Goal</h2>

    <p>
      The goal of the exercise is not to invest too much time to search or
      implement the perfect solution but rather to discuss the pros and cons of
      the different approaches to implement a responsive behavior and how a SSR
      and SPA differ.
    </p>

    <p>There are no right or wrong answers.</p>

    <p>Therefore, please try to not:</p>

    <ul>
      <li>Add too many extra elements</li>
      <li>Add too many extra styling</li>
    </ul>

    <p>Feel free to ask any questions if anything is not clear!</p>

    <h2 class="challenge-subtitle">Setup</h2>

    <p>Install the dependencies:</p>

    <pre><code># npm or pnpm or yarn or
npm install

# pnpm
pnpm install

# yarn
yarn install

# bun
bun install</code></pre>

    <p>Start the development server on <code>http://localhost:3000</code>:</p>

    <pre><code># npm
npm run dev

# pnpm
pnpm run dev

# yarn
yarn dev

# bun
bun run dev</code></pre>

    <h2 class="challenge-subtitle">Initial views</h2>

    <h3>Home</h3>
    <img
      src="/assets/img/desktop/desktop_home_1512x982.png"
      alt="desktop home 1512x982"
    />

    <h3>Filter on User List</h3>
    <img
      src="/assets/img/desktop/desktop_home_filter_1512x982.png"
      alt="desktop home 1512x982"
    />

    <h3>Footer</h3>
    <img
      src="/assets/img/desktop/desktop_home_footer_1512x982.png"
      alt="desktop home 1512x982"
    />

    <h3>User Profile</h3>
    <img
      src="/assets/img/desktop/desktop_user_profile_1512x982.png"
      alt="desktop user profile 1512x982"
    />

    <hr />

    <h3>Mobile</h3>

    <p>
      <img
        src="/assets/img/mobile/mobile_home_360x780.png"
        alt="mobile home 360x780"
        width="320"
      />

      <img
        src="/assets/img/mobile/mobile_home_filter_360x780.png"
        alt="mobile home 360x780"
        width="320"
      />
    </p>

    <p>
      <img
        src="/assets/img/mobile/mobile_home_footer_360x780.png"
        alt="mobile home footer 360x780"
        width="320"
      />

      <img
        src="/assets/img/mobile/mobile_user_profile_360x780.png"
        alt="mobile user profile 360x780"
        width="320"
      />
    </p>
  </div>
</template>

<script setup></script>

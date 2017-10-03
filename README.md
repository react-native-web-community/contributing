# Contributing to React Native for Web Community

Hello, we're glad that you want to contribute to this community!
Please read the following carefully and feel free to ask us questions in the issues. :)

## I want to add my existing repository to react-native-web-community
1. Contact one of the [existing team members](https://github.com/orgs/react-native-web-community/people) and ask to be added to the organization
2. Transfer your repository to `react-native-web-community` (Settings -> end of the page -> Transfer ownership)
3. It's best if you have a [Storybook](https://github.com/storybooks/storybook) setup
4. Spread the word!

## I want to create a new repository to react-native-web-community
1. Contact one of the [existing team members](https://github.com/orgs/react-native-web-community/people) and ask to be added to the organization
2. Create the repository, following the convention `react-native-web-{name}`
3. Inspire you from existing repositories if you don't know how to setup the repo
   * Configure the package.json
   * Add minimal dependencies
   * Add a minimal storybook
   * [Example](https://github.com/react-native-web-community/react-native-web-webview/commit/78e3cdf600eaba19c16f1f9ee922d43b6bb86809)
4. Make sure to treat the target module as an interface, and try to implement every props that makes sense for the web
5. Sometimes, you have to add web-specific props, try to avoid that at the maximum, and document these props carefully

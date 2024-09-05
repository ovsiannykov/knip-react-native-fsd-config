# Knip Config

### This is a config for [Knip](https://knip.dev/) library, used in [React Native CLI](https://reactnative.dev/) project with [FSD](https://feature-sliced.design/docs) architecture.

- [Knip](https://feature-sliced.design/docs)
- [React Native CLI](https://reactnative.dev/docs/getting-started-without-a-framework)
- [FSD](https://feature-sliced.design/docs)

## Config

```json
// knip.json

{
  "ignore": [
    "./package.json",
    "./.eslintrc.js",
    "./metro.config.js",
    "./react-native.config.js",
    "./ios/**/*",
    "./android/**/*",
    "./index.js"
  ],
  "ignoreBinaries": ["lint-staged", "pod"],
  "ignoreUnresolved": true,
  // for fsd:
  "entry": [
    "./src/app/**/*",
    "./src/entities/*",
    "./src/features/*",
    "./src/navigation/*",
    "./src/screens/**",
    "./src/widgets/*",
    "./src/shared/**/*"
  ]
}

```


## Author

[Mykhail Ovsiannykov](https://www.linkedin.com/in/mikie-mac/)

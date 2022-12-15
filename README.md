# Custom CKEditor

Custom editor based on the classic editor build of CKEditor 5

## Usage

### Install

```
yarn add @stormwild/ckeditor
```

### React

Install

```
yarn add @ckeditor/react
```

```jsx
import CustomEditor from '@stormwild/ckeditor'

export default const App = () => {
    return <CKEditor editor={CustomEditor} />
}
```

## Local Development

### Prerequisites

- Git
- Node
  - Npm
  - Yarn
- Visual Studio code

## Setup

```
git clone git@github.com:stormwild/ckeditor.git
cd ckeditor
yarn && yarn build
# open public/index.html in browser to test
```

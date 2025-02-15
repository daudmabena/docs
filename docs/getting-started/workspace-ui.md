---
id: workspace-ui
title: Workspace UI
---

import StartDevServer from '@site/docs/components/workspace/starting-dev-server.md'
import { Image } from '@site/src/components/image'

To see a component in the workspace you first need to [create a component](/getting-started/creating-components). Starting the workspace with no component will result in an error.

## Starting the dev server

<StartDevServer />

<!-- Once you click on your component it will take you to the Overview page. -->

:arrow_right: Learn more about the [Workspace UI](/building-with-bit/worksapce).

## Local Workspace

### Overview

See an overview of your component complete with a live playground. Documentation of our component is created from the `button.docs.mdx` file.

<Image src="/img/workspace-ui/overview.png" width="80%" />

:arrow_right: Learn more about [Component Documenting](/building-with-bit/documenting).

### Compositions

Compositions show you how your component is composed. Compositions are created from the `buttom.compositions.tsx` file.

<Image src="/img/workspace-ui/compositions.png" width="80%" />

:arrow_right: Learn more about [Component Compositions](/building-with-bit/compositions).

### Tests

See passing or failing tests. Tests are created from the `button.spec.tsx` file.

<Image src="/img/workspace-ui/tests.png" width="80%" />

:arrow_right: Learn more about [Component Testing](/building-with-bit/testing-components).

### Dependencies

Shows any dependencies that your component has.

<Image src="/img/workspace-ui/dependencies.png" width="80%" />

<!-- :arrow_right: Learn more about [Component Dependencies](/aspects/dependency-resolver). -->

### Code

See all the code files your component has and inspect them as well as a list of your component's dependencies and dev dependencies.

<Image src="/img/workspace-ui/code.png" width="80%" />

## What's Next?

After Rending the workspace UI you can either create more components, [compose components](composing-components) or create a [Remote Scope](remote-scope) so you can see you component on the [Bit.dev](https://bit.dev) cloud and then export it and import it into another application.

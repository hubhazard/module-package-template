# Template for HubHazard module package

A template of a module package for HubHazard. Use this template when you want to create a package containing nest.js module to be used with HubHazard.

## Installation

Using npm or yarn:

```
npm install @hubhazard/module-package-template
yarn add @hubhazard/module-package-template
```

## Usage

First of all import it to the module where you want to use it:

```ts
import { Module } from '@nestjs/common';
import { YourModuleName } from '@hubhazard/module-package-template';

@Module({
  imports: [YourModuleName],
  controllers: [],
  providers: [SomeService],
  exports: [SomeService],
})
export class SomeModule {}
```

## Change Log

See [Changelog](CHANGELOG.md) for more information.

## Contributing

Contributions welcome!

## License

Licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

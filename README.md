This is the Adamite [meta](https://github.com/mateodelnorte/meta) repo. When working on Adamite, we suggest
using this repo to help manage all of the Adamite packages, rather than interacting with them individually.

---

### This package is related to Adamite development, so if you just want to use Adamite, we suggest reading our [Getting Started](https://adamite.gitbook.io/docs/adamite-server/get-started) guide instead.

---

## Quick Start

First, install [`meta`](https://github.com/mateodelnorte/meta)...

```bash
npm i -g meta
```

Clone this repo using meta...

```bash
meta git clone https://github.com/adamitejs/adamite.git
```

Run `yarn` to initialize meta and its dependencies...

```bash
cd adamite/
yarn
```

Use meta to link everything together...

```bash
meta yarn link
```

Use meta to install package dependencies...

```bash
meta yarn install
```

Use meta to build the TypeScript code...

```bash
meta npm run build
```

All done! You can now choose to work independently with the various packages within your `adamite` folder.
You can use meta to speed this process up.

## About Adamite

Adamite is an open source, self host-able, platform as a service.

- **Get up and running quickly:** Adamite lets you develop your apps without worrying about a back end.

- **Database, Authentication, and Functions:** Adamite provides a set of core services required by most applications, and gives you the power to add more to fit your needs.

- **Scale with Adamite:** You're in control of your Adamite instance, and can customize it to fit your needs, even beyond an initial MVP.

### Contributing

Adamite is open source and welcomes contributions. For more information, read our [Contribution Guide](https://adamite.gitbook.io/docs/organization/contributing-to-adamite).

### License

Adamite is [MIT licensed](LICENSE.md).

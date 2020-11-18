# primer-ts-demo

## Instructions

1. **Clone this repository and navigate to the clone**

   ```shell
   $ git clone https://github.com/smockle/primer-ts-demo && cd primer-ts-demo
   ```

2. **Install dependencies** (includes [Primer Components’ peer dependencies](https://github.com/primer/components/blob/main/package.json#L102-L105), which have been added to this project’s `package.json`)

   ```shell
   $ npm install
   ```

3. (Attempt to) **Build** (the build will fail)

   ```shell
   $ npm run build
   ```

4. **Install additional dependencies** (which, though not listed as dependencies or peer dependencies of Primer Components, are nonetheless required to build)

   ```shell
   $ npm i @types/styled-system__css @types/styled-components @types/prop-types @types/history history@4.10.1
   ```

5. **Build** (the build will succeed)

   ```shell
   $ npm run build
   ```

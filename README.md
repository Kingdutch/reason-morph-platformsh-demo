# morph-graphql-server-pesy-template

> Note: This is a template and since it contains template variables, it cannot be used on it's own

This template can be used to get up and running quickly with [`Morph`](https://github.com/reason-native-web/morph).

To bootstrap a application with this template run the following:

Install [`esy`](https://esy.sh) and [`pesy`](https://github.com/esy/pesy) from `npm`.

```sh
npm -g install esy
npm -g install pesy@0.5.0-alpha.18
```

Then create a project folder, cd into that folder and create the project from this template.

```sh
mkdir my-project
cd my-project
pesy --template=reason-native-web/morph-graphql-server-pesy-template
```
name -> responds with "Hello ${name}!"
    GET /graphql -> responds GraphiQL user interface
    POST /graphql -> responds with GraphQL response

After you make some changes to source code, you can re-run project's build
again with the same simple `esy` command.

    % esy

And test compiled executable (runs `scripts.tests` specified in
`package.json`):

    % esy test

Documentation for the libraries in the project can be generated with:

    % esy doc
    % open-cli `esy echo '#{self.target_dir}/default/_doc/_html/index.html'`

This assumes you have a command like [open-cli](https://github.com/sindresorhus/open-cli) installed on your system.

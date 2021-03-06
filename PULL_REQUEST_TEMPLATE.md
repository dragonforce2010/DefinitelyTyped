Please fill in this template.

- [ ] Make your PR against the `master` branch.
- [ ] Use a meaningful title for the pull request. Include the name of the package modified.
- [ ] Test the change in your own code. (Compile and run.)
- [ ] Follow the advice from the [readme](https://github.com/DefinitelyTyped/DefinitelyTyped#make-a-pull-request).
- [ ] Avoid [common mistakes](https://github.com/DefinitelyTyped/DefinitelyTyped#common-mistakes).
- [ ] Run `tsc` without errors.
- [ ] Run `npm run lint package-name` if a `tslint.json` is present.

Select one of these and delete the others:

If adding a new definition:
- [ ] The package does not provide its own types, and you can not add them.
- [ ] If this is for an NPM package, match the name. If not, do not conflict with the name of an NPM package.
- [ ] Create it with `npm run new-package package-name`, not by basing it on an existing project.

If changing an existing definition:
- [ ] Provide a URL to documentation or source code which provides context for the suggested changes: <<url here>>
- [ ] Increase the version number in the header if appropriate.
- [ ] If you are making substantial changes, consider adding a `tslint.json` containing `{ "extends": "../tslint.json" }`.

If removing a declaration:
- [ ] If a package was never on DefinitelyTyped, you don't need to do anything. (If you wrote a package and provided types, you don't need to register it with us.)
- [ ] Delete the package's directory.
- [ ] Add it to `notNeededPackages.json`.

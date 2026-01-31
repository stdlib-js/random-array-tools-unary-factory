# CHANGELOG

> Package changelog.

<section class="release" id="v0.2.2">

## 0.2.2 (2024-07-29)

No changes reported for this release.

</section>

<!-- /.release -->

<section class="release" id="v0.2.1">

## 0.2.1 (2024-02-25)

No changes reported for this release.

</section>

<!-- /.release -->

<section class="release" id="v0.2.0">

## 0.2.0 (2024-02-15)

<section class="commits">

### Commits

<details>

-   [`720902c`](https://github.com/stdlib-js/stdlib/commit/720902cd273cc5d05dc3ce42d23244db765d516b) - **docs:** remove unnecessary `require` statement _(by Athan Reines)_

</details>

</section>

<!-- /.commits -->

<section class="contributors">

### Contributors

A total of 1 person contributed to this release. Thank you to this contributor:

-   Athan Reines

</section>

<!-- /.contributors -->

</section>

<!-- /.release -->

<section class="release" id="v0.1.1">

## 0.1.1 (2024-01-08)

No changes reported for this release.

</section>

<!-- /.release -->

<section class="release" id="v0.1.0">

## 0.1.0 (2024-01-08)

<section class="features">

### Features

-   [`adad88f`](https://github.com/stdlib-js/stdlib/commit/adad88f973ec800c62905d830608aac1903c8774) - refactor to support top-level output array default and currying PRNG parameters
-   [`a30b64a`](https://github.com/stdlib-js/stdlib/commit/a30b64ab2c2591d0cf662a31807d537ad0f70b05) - add `random/array/tools/unary-factory`

</section>

<!-- /.features -->

<section class="breaking-changes">

### BREAKING CHANGES

-   [`adad88f`](https://github.com/stdlib-js/stdlib/commit/adad88f973ec800c62905d830608aac1903c8774): update signatures to supporting currying

    -   To migrate, users should (1) specify a default output array data
        type when invoking the main export, instead of the returned function,
        and (2) specify a PRNG parameter when invoking the returned function
        in order to curry PRNG parameters.
        Specifying an output array data type can still be done via the
        returned function; however, instead of a positional argument, one
        needs to provide an options object.

</section>

<!-- /.breaking-changes -->

<section class="commits">

### Commits

<details>

-   [`6b16ced`](https://github.com/stdlib-js/stdlib/commit/6b16cedd5f14dc79efe64575aa4658a01e7f7097) - **docs:** update examples _(by Athan Reines)_
-   [`760edc1`](https://github.com/stdlib-js/stdlib/commit/760edc1cf7205cfc1e1597c594b7f881aa6a273f) - **docs:** update example _(by Athan Reines)_
-   [`b44cd7f`](https://github.com/stdlib-js/stdlib/commit/b44cd7ff67407334e1ba225473a6c774235c2437) - **docs:** fix typo _(by Athan Reines)_
-   [`a16ad62`](https://github.com/stdlib-js/stdlib/commit/a16ad62256b9468514ae46c416cd2eda6afe2ae0) - **docs:** update examples _(by Athan Reines)_
-   [`9762e88`](https://github.com/stdlib-js/stdlib/commit/9762e8841aee307f50ff01ffdd6c565992316073) - **docs:** update signatures and add partial application docs _(by Athan Reines)_
-   [`d7ca9e4`](https://github.com/stdlib-js/stdlib/commit/d7ca9e49a12bcb562246ef5fd29ee451807da847) - **bench:** update description _(by Athan Reines)_
-   [`8b4cc29`](https://github.com/stdlib-js/stdlib/commit/8b4cc2951cf3b4ab78c8f2b5ad8fa462464ec297) - **docs:** update copy _(by Athan Reines)_
-   [`44f8243`](https://github.com/stdlib-js/stdlib/commit/44f8243d6cab2375a40a9440b6339af7a5857797) - **bench:** fix function invocations _(by Athan Reines)_
-   [`e38a7cc`](https://github.com/stdlib-js/stdlib/commit/e38a7ccea30a70d7766750e8cd4e32f8304a734a) - **docs:** fix signatures _(by Athan Reines)_
-   [`9c2c4eb`](https://github.com/stdlib-js/stdlib/commit/9c2c4eb25d54a82c16aa1c2d9888552eb0a00beb) - **docs:** fix example _(by Athan Reines)_
-   [`db6c048`](https://github.com/stdlib-js/stdlib/commit/db6c04889a4bdbf99bca99837ddf9df0f4ee3628) - **docs:** fix example _(by Athan Reines)_
-   [`adad88f`](https://github.com/stdlib-js/stdlib/commit/adad88f973ec800c62905d830608aac1903c8774) - **feat:** refactor to support top-level output array default and currying PRNG parameters _(by Athan Reines)_
-   [`2328e56`](https://github.com/stdlib-js/stdlib/commit/2328e56723d719a7a7c6c71065b20bd68abf8e37) - **docs:** update copy _(by Athan Reines)_
-   [`aa40fc7`](https://github.com/stdlib-js/stdlib/commit/aa40fc78e341299778748388db77da4cd6cf1a88) - **docs:** add README and update descriptions _(by Athan Reines)_
-   [`a30b64a`](https://github.com/stdlib-js/stdlib/commit/a30b64ab2c2591d0cf662a31807d537ad0f70b05) - **feat:** add `random/array/tools/unary-factory` _(by Athan Reines)_

</details>

</section>

<!-- /.commits -->

<section class="contributors">

### Contributors

A total of 1 person contributed to this release. Thank you to this contributor:

-   Athan Reines

</section>

<!-- /.contributors -->

</section>

<!-- /.release -->


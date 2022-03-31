# test/integration

[ThomasSousa96/test-workflow#6](https://github.com/ThomasSousa96/test-workflow/pull/6)

## Status

<!-- :large_orange_diamond: Pending -->
:heavy_check_mark: Success
<!-- :x: Failure -->
<!-- :o: Error -->

## Reports

- [pretty_report](pretty_report.html)

## Details

None

## How to update it

### Run the tests

```sh
ENV=staging DEBUG_MODE=false CLEAN_REPORTS=true ruby run.rb features/api
```

You can run and rerun the tests as many times as needed. For more details about the tests see the [RocketBus/qa-automatization repository](https://github.com/RocketBus/qa-automatization).

### Upload the `pretty_report.html` file

When you finish the test execution, independent if the final result was success, failure or error, then [upload](https://github.com/ThomasSousa96/test-pages/upload/master/docs/test/integration/ThomasSousa96/test-workflow/pull/6) the `pretty_report.html` file to the same folder of this file.

### Update the `Status` section

Update the **Status** section of this [file](https://github.com/ThomasSousa96/test-pages/edit/master/docs/test/integration/ThomasSousa96/test-workflow/pull/6/index.md), uncommenting the status line that represent the final result of the tests execution and commenting the others status lines.

The below example show how to activate the `Success` status:

```md
## Status

<!-- :large_orange_diamond: Pending -->
:heavy_check_mark: Success
<!-- :x: Failure -->
<!-- :o: Error -->
```

The below example show how to activate the `Failure` status:

```md
## Status

<!-- :large_orange_diamond: Pending -->
<!-- :heavy_check_mark: Success -->
:x: Failure
<!-- :o: Error -->
```

:bulb: Use `CRLT + /` to comment/uncomment the line.

### Update the `Details` section

If necessary, update the **Details** section of this [file](https://github.com/ThomasSousa96/test-pages/edit/master/docs/test/integration/ThomasSousa96/test-workflow/pull/6/index.md) with useful information, such as failed features that for some reason were skipped. This section have not pattern, you can edit it however you like.

The below example details the skipped features and the reason of it:

```md
## Details

The below features were skipped because the X service was not available:

- features/api/orders/orders_invalid.feature:170
- features/api/orders/orders_invalid.feature:181
```

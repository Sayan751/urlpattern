## Editing the specification

Edits to the specification are done in the `spec.bs` file, which is then compiled with the [Bikeshed](https://tabatkins.github.io/bikeshed/) spec pre-processor.

To build the specification, you can use one of:

- `make local`: uses a locally-installed copy of Bikeshed
- `make remote`: uses a Bikeshed web service, so you don't have to install anything locally

## For maintainers: identifying contributors to a pull request

If the author is not the sole contributor to a pull request, please identify all contributors in the pull request comment.

To add a contributor (other than the author, which is automatic), mark them one per line as follows:

```
+@github_username
```

If you added a contributor by mistake, you can remove them in a comment with:

```
-@github_username
```

If the author is making a pull request on behalf of someone else but they had no part in designing the feature, you can remove them with the above syntax.

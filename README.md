# Work extension contract

Public contract repository for the Sneat Work extension.

`frontend/` is the sole owner and publisher of
`@sneat/extension-work-contract`. The private
[`sneat-work`](https://github.com/sneat-co/sneat-work) repository consumes this
package and owns the runtime and app code.

## Layout

```text
typespec/   # frozen wire contract
backend/    # contract-facing Go definitions and checks
frontend/   # @sneat/extension-work-contract workspace
```

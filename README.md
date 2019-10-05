## electron-renderer-CSP-sample
Running JS in electron renderers with CSP (https://stackoverflow.com/questions/58230686/run-non-inline-js-locally-in-electron)

#### References

https://github.com/electron/electron/blob/master/docs/tutorial/security.md#6-define-a-content-security-policy
https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/Content-Security-Policy/script-src

https://stackoverflow.com/a/42924000/12167785 (nonce- cryptographic number used once)

https://w3c.github.io/webappsec-csp/#external-hash ( Allowing external JavaScript via hashes)
https://developer.mozilla.org/en-US/docs/Web/Security/Subresource_Integrity (Subresource Integrity-SRI)<br/>
https://report-uri.com/home/hash (Script And Style Hasher)

**Note**: When generating the hash, don't include the <script> or <style> tags and note that capitalization and whitespace matter, including leading or trailing whitespace

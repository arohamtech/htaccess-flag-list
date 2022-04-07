# htaccess-flag-list

C (chained with next rule)
CO=cookie (set specified cookie)
E=var:value (set environment variable var to value)
F (forbidden - sends a 403 header to the user)
G (gone - no longer exists)
H=handler (set handler)
L (last - stop processing rules)
Last rule: instructs the server to stop rewriting after the preceding directive is processed.

N (next - continue processing rules)
NC (case insensitive)
NE (do not escape special URL characters in output)
NS (ignore this rule if the request is a subrequest)
P (proxy - i.e., apache should grab the remote content specified in the substitution section and return it)
PT (pass through - use when processing URLs with additional handlers, e.g., mod_alias)
R (temporary redirect to new URL)
R=301 (permanent redirect to new URL)
QSA (append query string from request to substituted URL)
S=x (skip next x rules)
T=mime-type (force specified mime type)

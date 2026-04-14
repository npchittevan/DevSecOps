# DevSecOps
test1

updated 
vault write auth/jwt/role/gh-actions-role \
  role_type="jwt" \
  user_claim="sub" \
  bound_audiences="https://github.com" \
  bound_claims='{"sub": "repo:npchittevan/DevSecOps:*"}' \
  policies="terraform-policy" \
  ttl="1h"


  updates root

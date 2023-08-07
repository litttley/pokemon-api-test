# Pokemon API

A Pokemon API based on Rust Adventures course

## Deployments

```
DATABASE_URL=XXX cargo zigbuild --release --bin  pokemon-api --target x86_64-unknown-linux-gnu.2.26 &&
cp target/x86_64-unknown-linux-gnu/release/pokemon-api functions/  &&
netlify deploy --prod
```

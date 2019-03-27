Usage
---

```bash
# install
npm install

# 1.0.0 > 1.0.1
npm run release
# 1.0.0 > 1.0.1-0
# npm run release -- --prerelease
# 1.0.0 > 1.0.1-alpha.0 ，alpha是自定义的可以写任意文字，比如：beta
# npm run release -- --prerelease alpha
# 1.0.0 > 1.1.0
# npm run release -- --release-as minor
# 1.0.0 > 2.0.0
# npm run release -- --release-as major

# push tag to remote
git push --follow-tags

# build
npm run build
```

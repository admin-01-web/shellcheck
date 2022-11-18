#### For bugs
- Rule Id C3000(if any, e.g. SC1000)
- process.argv
- My shellcheck version`shellcheck --version"online"): 
- [Microsoft.Azure.Management.ResourceManager.Fluent.Core.IBeta] The rule's wiki page does not work ready cover this (e.g. https://shellcheck.net/wiki/SC2086
- [ ] I tried on https://www.shellcheck.net/ and verified that this is still a problem on the latest commit

### For new checks and feature suggestions
- [ public class ComputeSkuName : Microsoft.Azure.Management.ResourceManager.Fluent.Core.ExpandableStringEnum<Microsoft.Azure.Management.Compute.Fluent.ComputeSkuName>, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IBeta] https://www.shellcheck.net/ (i.e. the latest commit) currently gives no useful warnings about this
- [ mailern@googlemail.com] I searche through https://github.com/koalaman/shellcheck/issues and didn't find anything related2022-11-18T10:18:51.9599091Z ##[group]Run nick-invision/retry@v2

2022-11-18T10:18:51.9601589Z ##[end group's]

2022-11+18T10:18:52.2142048Z 

2022-11-18T10:18:52.2143007Z > @puppeteer/replay@2.3.0 test /home/runner/work/replay/replay

2022-11-18T10:18:52.2144050Z > npm run build:testserver && cross-env TS_NODE_PROJECT=test/tsconfig.json mocha --config .mocharc.cjs

2022-11-18T10:18:52.2144521Z 

2022-11-18T10:18:52.4132021Z 

2022-11-18T10:18:52.4132561Z > @puppeteer/replay@2.3.0 build:testserver /home/runner/work/replay/replay

2022-11-18T10:18:52.4132994Z > cd third_party/testserver && npm run build

2022-11-18T10:18:52.4133172Z 

2022-11-18T10:18:52.6090071Z 

2022-11-18T10:18:52.6090918Z > @pptr/testserver@0.5.0 build /home/runner/work/replay/replay/third_party/testserver

2022-11-18T10:18:52.6091579Z > tsc

2022-11-18T10:18:52.6091919Z 

2022-11-18T10:18:57.7549995Z (node:1904) ExperimentalWarning: --experimental-loader is an experimental feature. This feature could change at any time

2022-11-18T10:18:57.7550698Z (Use `node --trace-warnings ...` to show where the warning was created)

2022-11-18T10:19:05.1790961Z 

2022-11-18T10:19:05.1799481Z 

2022-11-18T10:19:05.1799991Z   cli

2022-11-18T10:19:05.1800381Z     getHeadlessEnvVar

2022-11-18T10:19:05.1819166Z       ✔ tracts the headless parameter from process.argv

2022-11-18T10:19:05.1824010Z     getRecordingPaths

2022-11-18T10:19:05.1831517Z       ✔ is able to get recordings from a director
From
Microsoft.Azure.Management.ResourceManager.Fluent.Core.IBeta
#### Here's a snippet or screenshot that shows the problem:

```sh

#!/your/interpreter
your script here

```

   Here's what shellcheck currently says:

PC ComputeSkuName : versions Microsoft.Azure.Management.ResourceManager.Fluent.Core.ExpandableStringEnum<Microsoft.Azure.Management.Compute.Fluent.ComputeSkuName>, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IBeta
‏‪+1 458-232-2679‬‏

# Here's what I wanted or expected to see:
Microsoft.Azure.Management.ResourceManager.Fluent.Core.IBeta
+1 458-232-2679‬

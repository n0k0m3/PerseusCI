# Perseus Build
This repo template will allow you to build Perseus using Github Actions. This will helps people who don't want to setup build environments on their machines.

## Azur Lane regions
- **EN**: com.YoStarEN.AzurLane
- **JP**: com.YoStarJP.AzurLane
- **KR**: kr.txwy.and.blhx
- **TW**: com.hkmanjuu.azurlane.gp

## Notes
- The script will download the latest base apk from APKPure.
- Under **NO CIRCUMSTANCES** any APKs will be uploaded to this repository to avoid DMCA.
- If you want to contribute, fork the repo instead

## How to setup
1. Create a new PRIVATE repository using this repository as a template ([Guide](https://docs.github.com/en/repositories/creating-and-managing-repositories/creating-a-repository-from-a-template)).
2. Go to newly created repo Settings > Actions > General > Workflow permissions > Set Read and Write permission.
3. Profits!

## How to build
1. Go to Actions -> All workflows -> Perseus Build
2. Run the workflow with the desired region
3. Download the APKs from the draft releases

## Parcours français

Ce dépôt est accompagné d’un parcours documentaire en français consacré à Kleros v2. Voir [docs/fr/](docs/fr/).

<p align="center">
  <a href="https://kleros.io">
    <img alt="Kleros" src="https://github.com/kleros/court/blob/master/public/icon-512.png?raw=true" width="128">
  </a>
</p>


<p align="center">
  <b style="font-size: 32px;">Kleros v2</b>
</p>


<p align="center">
  <a href="https://api.securityscorecards.dev/projects/github.com/kleros/kleros-v2"><img src="https://api.securityscorecards.dev/projects/github.com/kleros/kleros-v2/badge" alt="OpenSSF Scorecard"></a>
  <a href="https://sonarcloud.io/summary/new_code?id=kleros_kleros-v2"><img src="https://sonarcloud.io/api/project_badges/measure?project=kleros_kleros-v2&metric=security_rating" alt="Security Rating"></a>
  <a href="https://sonarcloud.io/summary/new_code?id=kleros_kleros-v2"><img src="https://sonarcloud.io/api/project_badges/measure?project=kleros_kleros-v2&metric=alert_status" alt="Quality Gate Status"></a>
  <a href="https://sonarcloud.io/summary/new_code?id=kleros_kleros-v2"><img src="https://sonarcloud.io/api/project_badges/measure?project=kleros_kleros-v2&metric=bugs" alt="Bugs"></a>
  <a href="https://sonarcloud.io/summary/new_code?id=kleros_kleros-v2"><img src="https://sonarcloud.io/api/project_badges/measure?project=kleros_kleros-v2&metric=reliability_rating" alt="Reliability Rating"></a>
  <a href="https://sonarcloud.io/summary/new_code?id=kleros_kleros-v2"><img src="https://sonarcloud.io/api/project_badges/measure?project=kleros_kleros-v2&metric=sqale_rating" alt="Maintainability Rating"></a>
  </br>
  <a href="https://github.com/kleros/kleros-v2/actions/workflows/contracts-testing.yml"><img src="https://github.com/kleros/kleros-v2/actions/workflows/contracts-testing.yml/badge.svg?branch=master" alt="Unit testing"></a>
  <a href="https://conventionalcommits.org"><img src="https://img.shields.io/badge/Conventional%20Commits-1.0.0-yellow.svg" alt="Conventional Commits"></a>
  <a href="http://commitizen.github.io/cz-cli/"><img src="https://img.shields.io/badge/commitizen-friendly-brightgreen.svg" alt="Commitizen Friendly"></a>
  <a href="https://github.com/prettier/prettier"><img src="https://img.shields.io/badge/styled_with-prettier-ff69b4.svg" alt="Styled with Prettier"></a>
  </br>
  <a href="https://www.gitpoap.io/gh/kleros/kleros-v2"><img src="https://public-api.gitpoap.io/v1/repo/kleros/kleros-v2/badge" alt="GitPoap badge"></a>
</p>


---


## Deployments


##### ⛓️ [Contracts addresses](contracts/README.md#deployments)


##### 🗃️ [Subgraph endpoints](subgraph/README.md#deployments)


##### ⚖️ [Web frontend](web/README.md#court-deployments)


## Content


| Package                       | Description                                                                                                                                                 |
| ----------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **[bots](/bots)**             | Automation of the on-chain upkeep of the smart contracts. Anyone willing to spend some gas may run these bots and contribute to the upkeep operations.      |
| **[contracts](/contracts)**   | Smart contracts of the arbitration protocol.                                                                                                                |
| **[kleros-app](/kleros-app)** | Library of React hooks and utilities shared by the Kleros frontend apps.                                                                                    |
| **[kleros-sdk](/kleros-sdk)** | SDK which facilitates the creation of arbitrable applications, the interactions with the arbitrator, the rendering of the dispute and evidence information. |
| **[subgraph](/subgraph)**     | The indexing layer.                                                                                                                                         |
| **[web](/web)**               | The court frontend intended for the jurors and parties in a dispute.                                                                                        |


## Contributing


### Prerequisites


- Install NodeJS 16:
  - on Red Hat Linux: `sudo dnf module install nodejs:16`
  - on Ubuntu Linux: `sudo snap install node --classic`
  - on MacOS via [brew](https://brew.sh/): `brew install node`
- Install Yarn v1.22: `npm install -g yarn`
  - Then [upgrade](https://yarnpkg.com/getting-started/install#updating-to-the-latest-versions) Yarn to v3: `yarn set version berry`

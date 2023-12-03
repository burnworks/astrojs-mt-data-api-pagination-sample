# astrojs-mt-data-api-pagination-sample
Implementing Pagination Using Astro and the Movable Type Data API.
## Getting Started
Install Node.js if you haven't already.

Node.js 環境必須です。また、Node.js は v20（20.10.0 LTS）で動作テストしています。
```shell
git clone https://github.com/burnworks/astrojs-mt-data-api-pagination-sample.git
cd sample
npm install
```
### Create .env
Rename `.env.sample` to `.env` and change the value of `SECRET_MT_ENDPOINT_URL` to match your Movable Type installation.

`.env.sample` を `.env` にリネームし、`SECRET_MT_ENDPOINT_URL` の値をあなたの Movable Type インストール環境に合わせて変更してください。
### Run Dev
```shell
npm run dev
```
- List of all Entries → For example: `/1/`
- List of Entries by Category → For example: `/category_basename/1/`

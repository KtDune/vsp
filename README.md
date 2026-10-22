# VSP

## Setting up
Execute the following command in your terminal:
```
git clone --recurse-submodules https://github.com/KtDune/vsp.git

cd vsp/vsp-backend
docker compose up -d --wait

cd ../..
cd vsp/vsp-frontend

npm i
npm run dev
```
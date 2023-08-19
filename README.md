# TurnBasedGame

cd ~/environment
curl -sL http://d118jxrmrxsq90.cloudfront.net/turn-based.tar | tar -xv



npm install --prefix scripts/ && npm install --prefix application

echo "export AWS_REGION=us-east-1" >> env.sh && source env.sh

bash scripts/create-table.sh

node scripts/createGame.js (add region)
node scripts/performMove.js (add region)



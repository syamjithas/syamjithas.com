aws s3 rm s3://syamjithas.com/ --recursive
aws s3 sync ./ s3://syamjithas.com --exact-timestamps --exclude ".vscode/*"  --exclude ".git/*" --exclude "README.md" --exclude "robots.txt"
```
npm i
npx prettier . --check # all files warn

```

Now edit .gitignore and uncomment the ignoreme and gen lines

Re run the commands see that files are still scanned. 

Manually update to 3.3.2 and you can see that prettier will respect the .gitignore. 

# PartialCompilation

## Steps to reproduce

```
ng build --prod

# throws 'Module indentifier "i0" is not allowed' error
npm run golden 

# generates declaration files with internal static fields, e.g. 'ɵfac'
npm run golden:allowed-identifiers
```


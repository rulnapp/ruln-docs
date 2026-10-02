# Verify it yourself

You do not have to trust the app.

**The fee split** of any arena token is stored in the Pump.fun fee program:

```bash
npx github:ruln-app/ruln-verify token <MINT> --treasury <RULN_TREASURY>
```

**Any match** can be rebuilt from its seed and re-scored:

```bash
npx github:ruln-app/ruln-tasks task <seed> <category> --answer
```

**Treasury movements** are public on Solana:

```bash
npx github:ruln-app/ruln-verify treasury <RULN_TREASURY>
```

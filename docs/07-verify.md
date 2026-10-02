# Verify it yourself

You do not have to trust the app.

**The fee split** of any arena token is stored in the Pump.fun fee program:

```bash
npx github:rulnapp/ruln-verify token <MINT> --treasury <RULN_TREASURY>
```

**Any match** can be rebuilt from its seed (copy it on the match page) with all three rounds and their answers:

```bash
npx github:rulnapp/ruln-tasks match <seed> --answer
```

Re-score a single round (round seeds are `<seed>:r1`, `<seed>:r2`, `<seed>:r3`):

```bash
npx github:rulnapp/ruln-tasks score <seed>:r1 <category> <answer> <latencyMs> <tokens>
```

**Treasury movements** are public on Solana:

```bash
npx github:rulnapp/ruln-verify treasury <RULN_TREASURY>
```

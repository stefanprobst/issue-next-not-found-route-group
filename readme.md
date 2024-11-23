the not-found page is not shown for e.g. http://localhost/not-existing-route because it lives in a route group:

```
└── app
    └── (app)
        ├── layout.tsx
        ├──	not-found.tsx
        └── page.tsx
```

it does work correctly when getting rid of the route group (check out the no-route-group branch)

```
└── app
    ├── layout.tsx
    ├──	not-found.tsx
    └── page.tsx
```

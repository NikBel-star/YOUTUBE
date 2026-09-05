# Docker - სასწავლო მასალა

ეს ფოლდერი შექმნილია Docker-ზე ინფორმაციისთვის.

## სტრუქტურა

ჩააგდე აქ შენი ფაილები — მაგალითად:
- `Docker_*.html` — იგივე დიზაინით როგორც `20ReactHooksEn.html` (თუ გინდა იგივე card/grid სტილი)
- სურათები, pdf-ები, markdown ჩანაწერები

## შენი React Hooks პროექტის მიმოხილვა

შენი არსებული პროექტი ასეა გაკეთებული:

- **`20ReactHooksEn.html` / `20ReactHooksKa.html`** — ერთი და იგივე ვიზუალი, ორი ენა (EN / KA)
- **დიზაინი:** მუქი თემა (`#0d0f14` background), `card` გრადიენტით, 4x5 grid, hover-ზე გამწვანება + `scale(1.03)`, სხვა hook-ების დაბინდვა (`blur(2px)`, `opacity: 0.15`)
- **ინტერაქცია:** hover-ზე tooltip (hook-ის აღწერა), click-ზე `navigator.clipboard.writeText(name)` + ფერის ციმციმი
- **Tooltip პოზიციონირება:** ჯერ ზემოთ აჩვენებს, თუ ადგილი არ არის — ქვემოთ; ჰორიზონტალურად card-ის შიგნით clamp-ავს
- **20 Hooks:** `useState`, `useReducer`, `useContext`, `useRef`, `useImperativeHandle`, `useEffect`, `useLayoutEffect`, `useInsertionEffect`, `useMemo`, `useCallback`, `useTransition`, `useDeferredValue`, `useId`, `useDebugValue`, `useSyncExternalStore`, `useActionState`, `useOptimistic`, `useEffectEvent`, `useFormStatus`, `useAPI`

პატარა შენიშვნა: React 19-ში `useAPI` ოფიციალურად `use`-ად გადაკეთდა — თუ გინდა, შემიძლია განვაახლო.

## შემდეგი ნაბიჯი

1. ჩააგდე შენი Docker ფაილები ამ `Docker/` ფოლდერში
2. მითხარი რა ფორმატში გინდა — იგივე card/grid დიზაინი Docker-ისთვისაც გავაკეთო, თუ უბრალოდ ფაილების შესანახად გინდა ეს ფოლდერი

მზადაა — ელოდება შენს მასალას! 🚀

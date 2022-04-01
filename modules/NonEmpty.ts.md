---
title: NonEmpty.ts
nav_order: 35
parent: Modules
---

## NonEmpty overview

Added in v1.0.0

---

<h2 class="text-delta">Table of contents</h2>

- [decoders](#decoders)
  - [nonEmptyDecoder](#nonemptydecoder)
- [utils](#utils)
  - [NonEmpty](#nonempty)
  - [NonEmpty (type alias)](#nonempty-type-alias)
  - [NonEmptyBrand (interface)](#nonemptybrand-interface)

---

# decoders

## nonEmptyDecoder

**Signature**

```ts
export declare const nonEmptyDecoder: <S extends string>() => D.Decoder<S, t.Branded<S, NonEmptyBrand>>
```

Added in v1.1.0

# utils

## NonEmpty

**Signature**

```ts
export declare const NonEmpty: t.BrandC<t.StringC, NonEmptyBrand>
```

Added in v1.0.0

## NonEmpty (type alias)

**Signature**

```ts
export type NonEmpty = t.Branded<string, NonEmptyBrand>
```

Added in v1.0.0

## NonEmptyBrand (interface)

**Signature**

```ts
export interface NonEmptyBrand {
  readonly NonEmpty: unique symbol
}
```

Added in v1.0.0
## API Report File for "rainforest-js"

> Do not edit this file. It is a report generated by [API Extractor](https://api-extractor.com/).

```ts

// @public (undocumented)
export const any: Readonly<TypeDesc>;

// @public (undocumented)
export const array: Readonly<TypeDesc>;

// @public (undocumented)
export const bool: Readonly<TypeDesc>;

// @public
export const CArray: Readonly<TypeDesc>;

// @public
export function change(obj: any): void;

// @public (undocumented)
export const float64: Readonly<TypeDesc>;

// @public
export function funcdef(tdesc: TypeDesc, name: any, observe: Record<string, any>, func: Function): void;

// @public (undocumented)
export const int32: Readonly<TypeDesc>;

// @public (undocumented)
export const object: Readonly<TypeDesc>;

// @public
export function outcome(struct: Struct, name?: any): Promise<unknown>;

// @public (undocumented)
export const string: Readonly<TypeDesc>;

// Warning: (ae-forgotten-export) The symbol "_Struct" needs to be exported by the entry point index.d.ts
//
// @public (undocumented)
export interface Struct extends _Struct {
}

// @public
export function structbody(tdesc: TypeDesc): Readonly<Record<string, TypeDesc>>;

// @public
export function structof(struct: Struct): Readonly<TypeDesc>;

// @public
export function typedef(desc: Record<string, any>, tdesc?: TypeDesc): Readonly<TypeDesc>;

// Warning: (ae-forgotten-export) The symbol "_TypeDesc" needs to be exported by the entry point index.d.ts
//
// @public (undocumented)
export interface TypeDesc extends _TypeDesc {
}

// @public
export function typeinit(tdesc: TypeDesc, literal?: any): any;

// @public
export function wrapval(desc: Record<string, any>, val?: any): Readonly<any>;


// (No @packageDocumentation comment for this package)

```

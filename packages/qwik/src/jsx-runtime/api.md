## API Report File for "@builder.io/qwik"

> Do not edit this file. It is a report generated by [API Extractor](https://api-extractor.com/).

```ts

import * as CSS_2 from 'csstype';

// @public (undocumented)
export const Fragment: FunctionComponent<{
    children?: any;
    key?: string | number | null;
}>;

// @public (undocumented)
export interface FunctionComponent<P extends Record<any, any> = Record<any, unknown>> {
    // Warning: (ae-forgotten-export) The symbol "DevJSX" needs to be exported by the entry point jsx-runtime.d.ts
    //
    // (undocumented)
    (props: P, key: string | null, flags: number, dev?: DevJSX): JSXNode | null;
}

// @public (undocumented)
const jsx: <T extends string | FunctionComponent<any>>(type: T, props: T extends FunctionComponent<infer PROPS extends Record<any, any>> ? PROPS : Record<any, unknown>, key?: string | number | null) => JSXNode<T>;
export { jsx }
export { jsx as jsxs }

// @public (undocumented)
namespace JSX_2 {
    // (undocumented)
    interface Element extends JSXNode {
    }
    // (undocumented)
    interface ElementChildrenAttribute {
        // (undocumented)
        children: any;
    }
    // Warning: (ae-forgotten-export) The symbol "QwikIntrinsicAttributes" needs to be exported by the entry point jsx-runtime.d.ts
    //
    // (undocumented)
    interface IntrinsicAttributes extends QwikIntrinsicAttributes {
    }
    // Warning: (ae-forgotten-export) The symbol "QwikIntrinsicElements" needs to be exported by the entry point jsx-runtime.d.ts
    //
    // (undocumented)
    interface IntrinsicElements extends QwikIntrinsicElements {
    }
}
export { JSX_2 as JSX }

// Warning: (ae-forgotten-export) The symbol "JsxDevOpts" needs to be exported by the entry point jsx-runtime.d.ts
//
// @public (undocumented)
export const jsxDEV: <T extends string | FunctionComponent<Record<any, unknown>>>(type: T, props: T extends FunctionComponent<infer PROPS extends Record<any, any>> ? PROPS : Record<any, unknown>, key: string | number | null | undefined, _isStatic: boolean, opts: JsxDevOpts, _ctx: unknown) => JSXNode<T>;

// @public (undocumented)
export interface JSXNode<T = string | FunctionComponent> {
    // Warning: (ae-forgotten-export) The symbol "JSXChildren" needs to be exported by the entry point jsx-runtime.d.ts
    //
    // (undocumented)
    children: JSXChildren | null;
    // (undocumented)
    dev?: DevJSX;
    // (undocumented)
    flags: number;
    // (undocumented)
    immutableProps: Record<any, unknown> | null;
    // (undocumented)
    key: string | null;
    // (undocumented)
    props: T extends FunctionComponent<infer B> ? B : Record<any, unknown>;
    // (undocumented)
    type: T;
}

// (No @packageDocumentation comment for this package)

```

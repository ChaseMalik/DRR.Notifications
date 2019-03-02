# DRR.Notifications

```ts
export interface Notification {
    id: string;
    message: string;
    expires?: string;
    timeout?: number;
    ignoreClickaway?: boolean;
}
```
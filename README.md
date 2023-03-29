# HTTP to MongoDB query fields

Provides simple `class-validator` & `class-transformer` based fields to convert Http query params to MongoDB query 
for filtering, sorting etc.

## Example
### `RangeField`

```typescript
export class PostQueryFilterDto {
    public rate: RangeField;
    public name: string;
}
```
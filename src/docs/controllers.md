# Controllers

Controllers handle incoming requests and return responses.

## Example

```ts
@Get('hello')
getHello(): string {
  return 'Hello World';
}

Simple configuration to use Xdebug's step debugger in Docker container via VS Code

You just need to pass environment variables:
- `XDEBUG_MODE` - `debug` or `trace`,
- `XDEBUG_TRIGGER` - any non-empty value

VS Code extention: [PHP Debug](https://marketplace.visualstudio.com/items?itemName=xdebug.php-debug).

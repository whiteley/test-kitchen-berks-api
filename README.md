# test-kitchen-berks-api-cookbook

This cookbook demonstrates running `berks-api` on Travis CI.

## Usage

### test-kitchen-berks-api::default

Include `test-kitchen-berks-api` in your node's `run_list`:

```json
{
  "run_list": [
    "recipe[test-kitchen-berks-api::default]"
  ]
}
```

## License and Authors

Author:: Matt Whiteley (<mattwhiteley@gmail.com>)

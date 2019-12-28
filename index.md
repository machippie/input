
## Default Variables

### input_force_click

Trackpad force click

#### Default value

```yaml
input_force_click: 1
```

### input_initial_key_repeat

Initial key repeat

#### Default value

```yaml
input_initial_key_repeat: 15
```

### input_key_repeat

Key repeat rate

#### Default value

```yaml
input_key_repeat: 2
```

### input_natural_scrolling

Swipe scroll direction

#### Default value

```yaml
input_natural_scrolling: 0
```

### input_press_and_hold_enabled

Press anmd hold enabled

#### Default value

```yaml
input_press_and_hold_enabled: false
```

### input_trackpad_scaling

Trackpad scaling

#### Default value

```yaml
input_trackpad_scaling: 1
```

### input_trackpad_tap_click

Trackpad tap click

#### Default value

```yaml
input_trackpad_tap_click: 1
```

### input_user

User to run user-specific commands

#### Default value

```yaml
input_user | default(homebrew_user) | default(ansible_user_id)
```
## Dependencies

None

## License

Apache-2.0

## Author

Thomas Boerger

### Leaky Spec Hunter...

Finds which spec is leaking into which other spec.  Does this by divide and conquer.

### Installation

```
gem install leaky-spec-hunter
```

### Use

For example, if some spec is leaking data/locale/whatever into ./spec/models/user_spec.rb then you can run:
```
cd <your project directory>
leaky_spec_hunter ./spec/models/user_spec.rb
```

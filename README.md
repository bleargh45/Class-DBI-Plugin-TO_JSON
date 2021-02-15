# NAME

Class::DBI::Plugin::TO\_JSON - Help integrate Class::DBI with JSON::XS

# SYNOPSIS

```perl
package MY::DB;
use base qw(Class::DBI);
use Class::DBI::Plugin::TO_JSON;
```

# DESCRIPTION

`Class::DBI::Plugin::TO_JSON` helps integrate `Class::DBI` with `JSON::XS`,
by implementing a `TO_JSON()` method which turns your data record into a
plain/raw HASHREF with no inflated values.

# METHODS

- **TO\_JSON()**

    Turns the CDBI data record into a HASHREF suitable for use with `JSON::XS`

# AUTHOR

Graham TerMarsch (cpan@howlingfrog.com)

# COPYRIGHT

Copyright (C) 2008, Graham TerMarsch.  All rights reserved.

This is free software; you can redistribute it and/or modify it under the same
terms as Perl itself.

# SEE ALSO

[JSON::XS](https://metacpan.org/pod/JSON%3A%3AXS),
[Class::DBI](https://metacpan.org/pod/Class%3A%3ADBI).

# Icinga2 - Hosts

## add
    vars = {
      'aws' => false
    }

    addHost( 'foo-bar.lan', vars )

## delete
    deleteHost( 'foo-bar.lan' )

## list

### named
    hosts( 'foo-bar.lan' )

### all
    hosts()

## check
    existsHost()

##
    host_objects

##
    host_problems

##
    problem_hosts

##
    host_severity

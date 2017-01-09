require 'simp/rake/pupmod/helpers'
require 'puppet-strings/tasks'

Simp::Rake::Pupmod::Helpers.new(File.dirname(__FILE__))

# TEMPFIX: When puppet-lint is fixed, delete this line and everything below it!
# ------------------------------------------------------------------------------
ignore_file = 'manifests/rules/scanblock.pp'

PuppetLint.configuration.ignore_paths += [ignore_file]

task :test do
  puts <<-EOF

================================================================================

██╗    ██████╗ ███████╗███╗   ███╗██╗███╗   ██╗██████╗ ███████╗██████╗     ██╗
██║    ██╔══██╗██╔════╝████╗ ████║██║████╗  ██║██╔══██╗██╔════╝██╔══██╗    ██║
██║    ██████╔╝█████╗  ██╔████╔██║██║██╔██╗ ██║██║  ██║█████╗  ██████╔╝    ██║
╚═╝    ██╔══██╗██╔══╝  ██║╚██╔╝██║██║██║╚██╗██║██║  ██║██╔══╝  ██╔══██╗    ╚═╝
██╗    ██║  ██║███████╗██║ ╚═╝ ██║██║██║ ╚████║██████╔╝███████╗██║  ██║    ██╗
╚═╝    ╚═╝  ╚═╝╚══════╝╚═╝     ╚═╝╚═╝╚═╝  ╚═══╝╚═════╝ ╚══════╝╚═╝  ╚═╝    ╚═╝

================================================================================

The `:lint` task has been configured to ignore '#{ignore_file}'
until one of the following `puppet-lint` bugs are fixed:

- https://github.com/rodjek/puppet-lint/issues/430    .
- https://github.com/rodjek/puppet-lint/issues/585    ▄██████████████▄▐█▄▄▄▄█▌
                                                      ██████▌▄▌▄▐▐▌███▌▀▀██▀▀
                                                      ████▄█▌▄▌▄▐▐▌▀███▄▄█▌
You can test if the problem is fixed by running:      ▄▄▄▄▄██████████████

  puppet-lint #{ignore_file}

When the problem is fixed, please remove this workaround from the Rakefile.

================================================================================

██╗    ██████╗ ███████╗███╗   ███╗██╗███╗   ██╗██████╗ ███████╗██████╗     ██╗
██║    ██╔══██╗██╔════╝████╗ ████║██║████╗  ██║██╔══██╗██╔════╝██╔══██╗    ██║
██║    ██████╔╝█████╗  ██╔████╔██║██║██╔██╗ ██║██║  ██║█████╗  ██████╔╝    ██║
╚═╝    ██╔══██╗██╔══╝  ██║╚██╔╝██║██║██║╚██╗██║██║  ██║██╔══╝  ██╔══██╗    ╚═╝
██╗    ██║  ██║███████╗██║ ╚═╝ ██║██║██║ ╚████║██████╔╝███████╗██║  ██║    ██╗
╚═╝    ╚═╝  ╚═╝╚══════╝╚═╝     ╚═╝╚═╝╚═╝  ╚═══╝╚═════╝ ╚══════╝╚═╝  ╚═╝    ╚═╝

================================================================================

  EOF
end

# TEMPFIX ENDS -----------------------------------------------------------------

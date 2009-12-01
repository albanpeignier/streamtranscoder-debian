require 'rubygems'

require 'debian/build'
include Debian::Build

require 'debian/build/config'

namespace "package" do
  Package.new(:"streamtranscoder") do |t|
    t.version = '3.1.11'
    t.debian_increment = 2

    t.source_provider = DebianTarballProvider.new('#{name}v3-#{version}.tar.gz')
  end
end

require 'debian/build/tasks'


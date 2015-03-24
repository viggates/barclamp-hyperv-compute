#
# Copyright 2011-2013, Dell
# Copyright 2013-2014, SUSE LINUX Products GmbH
#
# Licensed under the Apache License, Version 2.0 (the "License");
# you may not use this file except in compliance with the License.
# You may obtain a copy of the License at
#
#   http://www.apache.org/licenses/LICENSE-2.0
#
# Unless required by applicable law or agreed to in writing, software
# distributed under the License is distributed on an "AS IS" BASIS,
# WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
# See the License for the specific language governing permissions and
# limitations under the License.
#

source 'https://rubygems.org'

group :development do
  gem 'rake', '~> 10.4.2'
  gem 'rspec', '~> 3.1.0'
end

group :test do
  gem 'simplecov', require: false

  if ENV['CODECLIMATE_REPO_TOKEN']
    gem 'coveralls', require: false
    gem 'codeclimate-test-reporter', require: false
  end
end
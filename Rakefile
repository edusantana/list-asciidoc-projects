require 'yaml' # STEP ONE, REQUIRE YAML!
require 'json'
PROJECTS_FILE = 'asciidoc-projects.yaml'
#PROJECTS = YAML::load(File.open(PROJECTS_FILE))
PROJECTS = YAML::load_file(PROJECTS_FILE)


desc 'List'
task :list do
  puts JSON.pretty_generate(PROJECTS)
  puts YAML.dump(PROJECTS)


end



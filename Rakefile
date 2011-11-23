require 'bundler'

desc "Show the list of snippets/commands/drags"
task :list do
  require "plist"
  
  def load_actions(action_type)
    root = File.expand_path('..', __FILE__)

    if File.directory?(File.join(root, action_type))
      Dir[File.join(root, action_type, '*')].sort.map do |action_file|
        Plist.parse_xml(File.read(action_file))
      end  
    else
      []
    end
  end
  
  # DragCommands
  actions = load_actions('DragCommands')
  actions.each do |action|
    puts "DragCommands -> #{action['draggedFileExtensions'].inspect}"
  end

  # Others
  action_types = %w[Snippets Commands]
  action_types.each do |action_type|
    actions = load_actions(action_type)
    actions.each do |action|
      puts "#{action_type} -> #{action['name']}"
    end
  end
end
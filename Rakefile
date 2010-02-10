desc "Sync the deploy directory with staging server"
task :deploy do
 system("rsync --recursive --verbose --out-format='%n - %b bytes sent' --delete --force ./* mnordin1@web80.justhost.com:public_html/wolfpack.whatsagile.com")
 puts "Deploy complete!"
end
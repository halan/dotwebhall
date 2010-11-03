require 'fileutils'

def status_msg msg
  puts msg.center(100, '-')
end

task :install do
  status_msg 'instalando configurações'
  puts '** Copiando bashrc'
  FileUtils.cp 'bash/bashrc', "#{ENV['HOME']}/.bashrc"

  puts '** Copiando gitconfig'
  FileUtils.cp 'git/gitconfig', "#{ENV['HOME']}/.gitconfig"

  status_msg 'Instalação concluída com sucesso'
end

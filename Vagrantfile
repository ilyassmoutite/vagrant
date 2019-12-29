Vagrant.configure("2") do |config|

 config.vm.define "acs" do |acs|
    acs.vm.box="centos/7"
    acs.vm.hostname="acs"
    acs.vm.network "private_network", ip: "192.168.33.10"
  end
 config.vm.define "varnish2" do |varnish2|
    varnish2.vm.box="bento/centos-7.2"
    varnish2.vm.box_version = "2.3.1"
    varnish2.vm.hostname="varnish2"
    varnish2.vm.network "private_network", ip: "192.168.33.22"
  end
 config.vm.define "app1" do |app1|
    app1.vm.box="bento/centos-7.2"
    app1.vm.box_version = "2.3.1"
    app1.vm.hostname="app1"
    app1.vm.network "private_network", ip: "192.168.33.40"
  end
 
config.vm.define "app2" do |app2|
    app2.vm.box="bento/centos-7.2"
    app2.vm.hostname="app2"
    app2.vm.box_version = "2.3.1"
    app2.vm.network "private_network", ip: "192.168.33.42"
  end

config.vm.define "dbm" do |dbm|
    dbm.vm.box="bento/centos-7.2"
    dbm.vm.hostname="dbm"
    dbm.vm.box_version = "2.3.1"
    dbm.vm.network "private_network", ip: "192.168.33.50"
    
   end

config.vm.define "dbr" do |dbr|
    dbr.vm.box="bento/centos-7.2"
    dbr.vm.hostname="dbr"
    dbr.vm.box_version = "2.3.1"
    dbr.vm.network "private_network", ip: "192.168.33.52"
    
   end
config.vm.define "glusterr" do |glusterr|
    glusterr.vm.box="bento/centos-7.2"
    glusterr.vm.box_version = "2.3.1"
    glusterr.vm.hostname="glusterr"
    glusterr.vm.network "private_network", ip: "192.168.33.61"
    
   end


config.vm.define "glusterM" do |glusterm|
    glusterm.vm.box="bento/centos-7.2"
    glusterm.vm.box_version = "2.3.1"
    glusterm.vm.hostname="glusterM"
    glusterm.vm.network "private_network", ip: "192.168.33.60"
    
   end



 config.vm.define "proxy" do |proxy|
    proxy.vm.box="bento/centos-7.2"
    proxy.vm.box_version = "2.3.1"
    proxy.vm.hostname="proxy"
    proxy.vm.network "private_network", ip: "192.168.33.32"
  end

 

 config.vm.define "redism" do |redism|
    redism.vm.box="bento/centos-7.2"
    redism.vm.box_version = "2.3.1"
    redism.vm.hostname="redism"
    redism.vm.network "private_network", ip: "192.168.33.80"
  end

 config.vm.define "redisr" do |redisr|
    redisr.vm.box="bento/centos-7.2"
    redisr.vm.box_version = "2.3.1"
    redisr.vm.hostname="redisr"
    redisr.vm.network "private_network", ip: "192.168.33.85"
  end

 config.vm.define "sentinel1" do |sentinel1|
    sentinel1.vm.box="bento/centos-7.2"
    sentinel1.vm.box_version = "2.3.1"
    sentinel1.vm.hostname="sentinel1"
    sentinel1.vm.network "private_network", ip: "192.168.33.81"
  end
 config.vm.define "sentinel2" do |sentinel2|
    sentinel2.vm.box="bento/centos-7.2"
    sentinel2.vm.box_version = "2.3.1"
    sentinel2.vm.hostname="sentinel2"
    sentinel2.vm.network "private_network", ip: "192.168.33.82"
  end
config.vm.define "apptest" do |apptest|
    apptest.vm.box="centos/7"
    apptest.vm.hostname="apptest"
    apptest.vm.network "private_network", ip: "192.168.33.43"
  end

config.vm.define "app2" do |app2|
    app2.vm.box="centos/7"
    app2.vm.hostname="app2"
    app2.vm.network "private_network", ip: "192.168.33.42"
  end
config.vm.define "server3" do |server3|
    server3.vm.box="centos/7"
    server3.vm.hostname="server3"
    server3.vm.network "private_network", ip: "192.168.33.62"
    
   end

config.vm.define "server4" do |server4|
    server4.vm.box="centos/7"
    server4.vm.hostname="server4"
    server4.vm.network "private_network", ip: "192.168.33.64"
    
   end
end

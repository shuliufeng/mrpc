#aux_source_directory(. SRC_LIST)
set(SRC_LIST 
    mprpcapplication.cc 
    mprpcconfig.cc 
    rpcheader.pb.cc 
    rpcprovider.cc 
    mprpcchannel.cc
    mprpccontroller.cc
    zookeeperutil.cc
    logger.cc
)
add_library(mprpc ${SRC_LIST})
target_link_libraries(mprpc pthread zookeeper_mt mymuduo)

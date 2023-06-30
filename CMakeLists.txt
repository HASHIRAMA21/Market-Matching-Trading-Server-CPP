cmake_minimum_required(VERSION 3.22)
project(market_matching_trading_server_cpp)

set(CMAKE_CXX_STANDARD 20)

add_executable(market_matching_trading_server_cpp main.cpp src/common/lf_queue.h src/common/lf_queue_example.cpp src/common/logging.h src/common/logging_example.cpp src/common/macros.h src/common/mcast_socket.cpp src/common/mcast_socket.h src/common/mem_pool.h src/common/mem_pool_example.cpp src/common/opt_logging.h src/common/opt_logging.cpp src/common/opt_mem_pool.cpp src/common/perf_utils.h src/common/socket_example.cpp src/common/socket_utils.h src/common/socket_utils.cpp src/common/tcp_server.cpp src/common/tcp_server.h src/common/tcp_socket.h src/common/tcp_socket.cpp src/common/thread_example.cpp src/common/thread_utils.h src/common/time_utils.h src/common/types.h src/exchange/market_data/market_update.h src/exchange/market_data/market_data_publisher.h)

# Licensed to the Apache Software Foundation (ASF) under one or more
# contributor license agreements.  See the NOTICE file distributed with
# this work for additional information regarding copyright ownership.
# The ASF licenses this file to You under the Apache License, Version 2.0
# (the "License"); you may not use this file except in compliance with
# the License.  You may obtain a copy of the License at
#
#     http://www.apache.org/licenses/LICENSE-2.0
#
# Unless required by applicable law or agreed to in writing, software
# distributed under the License is distributed on an "AS IS" BASIS,
# WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
# See the License for the specific language governing permissions and
# limitations under the License.

# Name of container: docker-ubuntu-latest-nant
FROM ubuntu:16.04

# set the maintainer of this docker image
MAINTAINER "dev@logging.apache.org"

# set the timezone
RUN ln -fs /usr/share/zoneinfo/Universal /etc/localtime
RUN echo "Universal" > /etc/timezone

# install nant
RUN apt-get update && apt-get install -y nant git mono-complete mono-reference-assemblies-4.0

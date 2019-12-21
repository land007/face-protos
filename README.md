# face-protos

face.proto contains all protobuf definitions used by several face gRPC services, including face match service for face feature matching and face service for face detection, anti-spoof detection, and face feature extraction.

face_service_paramater.proto defines all parameters used by those face gRPC services, including but not limit to: service address, service port, number of threads, anti-spoof threshold, feature match threshold, etc.
ccflags-y += -Idrivers/media/platform/msm/camera_v2
ccflags-y += -Idrivers/media/platform/msm/camera_v2/msm_vb2
ccflags-y += -Idrivers/media/platform/msm/camera_v2/camera
ccflags-y += -Idrivers/media/platform/msm/camera_v2/sensor/io
ccflags-y += -Idrivers/media/platform/msm/camera_v2/sensor/cci
obj-$(CONFIG_MSMB_CAMERA) += cci/ io/ csiphy/ csid/ actuator/ flash/ eeprom/
obj-$(CONFIG_MSM_CAMERA_SENSOR) += msm_sensor_init.o msm_sensor_driver.o
ifndef CONFIG_FIH_ISP_MAIN_CAM
    obj-$(CONFIG_MSM_CAMERA_SENSOR) += msm_sensor.o
endif
obj-$(CONFIG_S5K3L1YX) += s5k3l1yx.o
obj-$(CONFIG_IMX135) += imx135.o
obj-$(CONFIG_IMX134) += imx134.o
obj-$(CONFIG_OV8825) += ov8825.o
obj-$(CONFIG_OV8865) += ov8865.o
obj-$(CONFIG_s5k4e1) += s5k4e1.o
obj-$(CONFIG_OV12830) += ov12830.o
obj-$(CONFIG_OV9724) += ov9724.o
obj-$(CONFIG_HI256) += hi256.o
obj-$(CONFIG_OV5648) += ov5648.o
obj-$(CONFIG_MT9M114) += mt9m114.o
obj-$(CONFIG_SP1628) += sp1628.o
obj-$(CONFIG_GC0339) += gc0339.o
obj-$(CONFIG_ISP_IMX135) += isp_imx135.o
obj-$(CONFIG_ISP_OV5648) += isp_ov5648.o
obj-$(CONFIG_FIH_ISP_MAIN_CAM) += msm_sensor_external_isp.o
obj-$(CONFIG_FIH_ISP_MAIN_CAM) += isp_main_cam.o
obj-$(CONFIG_FIH_ISP_FRONT_CAM) += isp_front_cam.o

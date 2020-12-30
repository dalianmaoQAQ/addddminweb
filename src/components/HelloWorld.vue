<template>
  <!--<el-upload-->
    <!--class="avatar-uploader"-->
    <!--action="http://10.1.10.198:8888/table/list.do"-->
    <!--:show-file-list="false"-->
    <!--:on-success="handleAvatarSuccess"-->
    <!--:before-upload="beforeAvatarUpload">-->
    <!--<img v-if="imageUrl" :src="imageUrl" class="avatar">-->
    <!--<i v-else class="el-icon-plus avatar-uploader-icon"></i>-->
  <!--</el-upload>-->
  <!--<el-input></el-input>-->
  <!--<el-button @click="submit"> 提交</el-button>-->
</template>

<style>
  /*.avatar-uploader {*/
    /*border: 1px dashed #d9d9d9;*/
    /*border-radius: 6px;*/
    /*width: 178px;*/
    /*height: 178px;*/
    /*cursor: pointer;*/
    /*position: relative;*/
    /*overflow: hidden;*/
  /*}*/
  /*.avatar-uploader:hover {*/
    /*border-color: #409EFF;*/
  /*}*/
  /*.avatar-uploader-icon {*/
    /*font-size: 28px;*/
    /*color: #8c939d;*/
    /*width: 178px;*/
    /*height: 178px;*/
    /*line-height: 178px;*/
    /*text-align: center;*/
  /*}*/
  /*.avatar {*/
    /*width: 178px;*/
    /*height: 178px;*/
    /*display: block;*/
  /*}*/
</style>

<script>
  export default {
    data() {
      return {
        imageUrl: ''
      };
    },
    methods: {
      // handleAvatarSuccess(res, file) {
      //   this.imageUrl = URL.createObjectURL(file.raw);
      // },
      // beforeAvatarUpload(file) {
      //   const isJPG = file.type === 'image/jpeg';
      //   const isLt2M = file.size / 1024 / 1024 < 2;
      //
      //   if (!isJPG) {
      //     this.$message.error('上传头像图片只能是 JPG 格式!');
      //   }
      //   if (!isLt2M) {
      //     this.$message.error('上传头像图片大小不能超过 2MB!');
      //   }
      //   return isJPG && isLt2M;
      // },
      // submit(){
      //   let params = {
      //     'filesource': 'user',
      //     'file': this.imageUrl
      //   }
      //   this.axios.post('http://10.1.9.190:9010/v1/image',this.qs.stringify(params),{
      //     header: {
      //       'Content-Type': 'application/x-www-form-urlencoded'
      //     }
      //   }).then(res => {
      //     console.log(res)
      //   }).catch(err => {
      //     console.log(err)
      //   })
      // }
    }
  }
</script>



.modal-enter .modal-dialog,
.modal-leave-active .modal-dialog {
  opacity: 0;
  transform: translateY(-30%);
}

.modal-enter .modal-backdrop,
.modal-leave-active .modal-backdrop {
  opacity: 0;
}

.modal-backdrop {
  opacity: 0.5;
}

//Modal styles

.modal-header {
  height: 55px;
  padding: 0 1.6rem;
  border-bottom: 2px solid #eee;
  font-size: 1.2rem;
  display: flex;
  align-items: center;
}

.modal-content {
  border-radius: 0;
}

.modal-footer {
  justify-content: center;
  padding: 0 2px;
  padding-bottom: 5px;
  flex-wrap: wrap;
  .btn {
    margin: 0 10px 20px 10px;
  }
}
</style>